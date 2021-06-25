

## Example Protractor project that:
* Makes use of page objects
* Runs tests on [Sauce Labs](http://saucelabs.com)
* Runs multiple browsers at once
* Runs tests sharded (parallel)


## Setup:
* Install [Node](http://nodejs.org) (v8.x.x or later)
* `npm i` to install the project dependencies

## Run tests:
* run tests via plain Protractor `node_modules/.bin/protractor conf.js`
* run tests `npm test` (runs via flake, which re-runs failed tests)
* run with flake `./flake conf.js`
* run on saucelabs`./flake sauceConf.js` (add your username/key)

