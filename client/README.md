# client

> A Vue.js project with Express.js (webpack template)

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Axios

Library to do those http requests to the backend

`npm install --save axios`

in src folder, make new folder called services

## Access Tokens

## Application state
the vuxe store manages the application's state. It's for checking for the currently logged in user's information so that we don't have to check the locally stored access token repeatedly.
