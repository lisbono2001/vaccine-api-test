# Tests for Vaccination provider site by [Suchon Site](https://github.com/SuchonSite/Server)

author Theetouch Kasemarnontana

For the tests result
see project [wiki](https://github.com/lisbono2001/vaccine-api-test/wiki)

## Getting Start
### for npm users
Install testing tool packages
```
npm install
```
How to run all tests?
```
npm run test
```
### for yarn users
Install testing tool packages
```
yarn
```
How to run all tests?
```
yarn test
```

---
## Tools in this project
### Jest
#### Setting up Jest
Install the jest package (and optional typings) to a new or existing project's package.json file using your package manager of choice:
```
# For NPM users
npm install --save-dev jest @types/jest

# Yarn users
yarn add --dev jest @types/jest
```
#### How to run tests with Jest?
To run tests with Jest call the jest command inside the root of the project folder.

Then update the project's **package.json** with a test script that calls the jest command for us:
```
{
    // ... package.json contents
    "scripts": {
        // ... existing scripts
        "test": "jest"
    }
}
```
We can now run the newly created test script:
```
# NPM users
npm run test

# Yarn users
yarn run test
```
### Axios
#### Setting up Axios

We will be using axios as our HTTP client. Axios is a lightweight, promise-based HTTP client for Node.js which can also be used by web browsers.
```
npm i axios --save-dev
```
File called **axiosConfig.js** is configuration of the Axios client. Configuring the client allows us to use common settings across a set of HTTP requests.
