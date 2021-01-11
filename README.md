# simple-licensing-api

Simple Licensing API is a simple and ready to use API to manage your software license. 

It generates license keys in bulk, and provides a simple RESTful + JSON API to activate and validate a license key from any device on which your app runs. 

## DEMO

Check out the [live demo](http://simple-licensing-api.magictek.cn).

## How to install

1. Make sure you already have MongoDB installed.
2. Clone this repository.
3. Run `npm install` or `yarn install` to install all the dependencies.
4. Run `npm run watch` to build the client-side javascript using webpack.
5. Copy `config.sample.js` to `config.js` and make changes to the configuration according to your specific environments.
6. Run `node ./bin/www.js`.
7. Visit `http://localhost:3352/` from your browser.
