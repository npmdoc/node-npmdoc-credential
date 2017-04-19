# npmdoc-credential

#### api documentation for  [credential (v2.0.0)](https://github.com/ericelliott/credential#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-credential.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-credential) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-credential.svg)](https://travis-ci.org/npmdoc/node-npmdoc-credential)

#### Easy password hashing and verification in Node. Protects against brute force, rainbow tables, and timing attacks.

[![NPM](https://nodei.co/npm/credential.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/credential)

- [https://npmdoc.github.io/node-npmdoc-credential/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-credential/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-credential/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-credential/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-credential/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-credential/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Elliott"
    },
    "bin": {
        "credential": "bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/ericelliott/credential/issues"
    },
    "dependencies": {
        "commander": "^2.8.1",
        "mout": "1.0.0",
        "pify": "^2.3.0",
        "pinkie-promise": "^2.0.0",
        "pluck-keys": "^0.0.4"
    },
    "description": "Easy password hashing and verification in Node. Protects against brute force, rainbow tables, and timing attacks.",
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-core": "^6.5.2",
        "babel-eslint": "6.0.4",
        "babel-loader": "^6.2.2",
        "babel-plugin-object-assign": "^1.2.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-stage-3": "^6.5.0",
        "blue-tape": "^0.2.0",
        "cross-env": "^1.0.5",
        "dependency-check": "^2.5.0",
        "eslint": "2.13.0",
        "eslint-config-xo-space": "0.14.0",
        "eslint-loader": "^1.2.1",
        "faucet": "0.0.1",
        "isparta": "^4.0.0",
        "node-libs-browser": "^1.0.0",
        "nsp": "^2.0.1",
        "precommit-hook": "^3.0.0",
        "rimraf": "^2.5.2",
        "tape": "^4.2.2",
        "ttest": "^0.3.0",
        "updtr": "0.1.15",
        "webpack": "^1.12.13"
    },
    "directories": {
        "test": "test",
        "bin": "bin"
    },
    "dist": {
        "shasum": "0dc30012e1b3caf3a8c4fa088a0ac158fee3ee46",
        "tarball": "https://registry.npmjs.org/credential/-/credential-2.0.0.tgz"
    },
    "gitHead": "b957f742758ac473984f69e69b8e07cb609bd646",
    "homepage": "https://github.com/ericelliott/credential#readme",
    "keywords": [
        "password",
        "passwords",
        "hash",
        "auth",
        "authorization",
        "authentication",
        "security",
        "login",
        "sign in",
        "salt",
        "rainbow",
        "brute",
        "stretching",
        "PBKDF2"
    ],
    "license": "MIT",
    "main": "credential.js",
    "maintainers": [
        {
            "name": "ericelliott"
        },
        {
            "name": "thomas-jensen"
        }
    ],
    "name": "credential",
    "optionalDependencies": {},
    "pre-commit": [
        "validate"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ericelliott/credential.git"
    },
    "scripts": {
        "audit": "nsp check",
        "build": "cross-env NODE_ENV=production webpack && npm run build:min",
        "build:min": "cross-env NODE_ENV=production MINIFY=1 webpack",
        "check": "npm run audit && npm outdated --depth 0",
        "clean": "rimraf build",
        "cov": "npm run cov:clean",
        "cov:clean": "rimraf coverage",
        "init": "rimraf .validate.json && rimraf .jshintrc",
        "lint": "eslint credential.js test bin/cmd.js",
        "prebuild": "npm run clean",
        "precheck": "npm run validate",
        "prepublish": "npm run build",
        "start": "webpack --watch",
        "test": "tape test/*-test.js",
        "update": "updtr",
        "validate": "npm run lint && npm run build && npm test",
        "validate-dev": "npm run lint && npm test | faucet"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
