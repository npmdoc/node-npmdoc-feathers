# npmdoc-feathers

#### api documentation for  [feathers (v2.1.1)](http://feathersjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-feathers.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-feathers) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-feathers.svg)](https://travis-ci.org/npmdoc/node-npmdoc-feathers)

#### Build Better APIs, Faster than Ever.

[![NPM](https://nodei.co/npm/feathers.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/feathers)

- [https://npmdoc.github.io/node-npmdoc-feathers/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-feathers/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-feathers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-feathers/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-feathers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-feathers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feathers",
        "url": "http://feathersjs.com"
    },
    "browser": {
        "./lib/index": "./lib/client/index"
    },
    "bugs": {
        "url": "https://github.com/feathersjs/feathers/issues"
    },
    "contributors": [
        {
            "name": "Eric Kryski",
            "url": "http://erickryski.com"
        },
        {
            "name": "David Luecke",
            "url": "http://neyeon.com"
        }
    ],
    "dependencies": {
        "@types/express": "~4.0.35",
        "babel-polyfill": "^6.20.0",
        "debug": "^2.6.0",
        "events": "^1.1.1",
        "express": "^4.14.0",
        "feathers-commons": "^0.8.7",
        "rubberduck": "^1.1.1",
        "uberproto": "^1.2.0"
    },
    "description": "Build Better APIs, Faster than Ever.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-core": "^6.21.0",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.18.0",
        "body-parser": "^1.15.2",
        "eslint-if-supported": "^1.0.1",
        "feathers-rest": "^1.5.3",
        "feathers-socketio": "^1.4.2",
        "istanbul": "^1.1.0-alpha.1",
        "jshint": "^2.9.4",
        "mocha": "^3.2.0",
        "nsp": "^2.6.2",
        "q": "^1.4.1",
        "request": "^2.x",
        "rimraf": "^2.5.4",
        "semistandard": "^9.2.1",
        "socket.io-client": "^1.7.2"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "d44b19a76c570c6c47b371615bc25a5e0a53efb4",
        "tarball": "https://registry.npmjs.org/feathers/-/feathers-2.1.1.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "7297b8d23b1c7226786a1851eab62495acf6d0c9",
    "homepage": "http://feathersjs.com",
    "keywords": [
        "feathers",
        "REST",
        "socket.io",
        "realtime"
    ],
    "license": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "ekryski"
        },
        {
            "name": "daffl"
        }
    ],
    "name": "feathers",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/feathersjs/feathers.git"
    },
    "scripts": {
        "compile": "rimraf lib/ && babel -d lib/ src/",
        "coverage": "istanbul cover node_modules/mocha/bin/_mocha -- --opts mocha.opts",
        "lint": "eslint-if-supported semistandard --fix",
        "mocha": "mocha --opts mocha.opts",
        "prepublish": "npm run compile",
        "publish": "git push origin && git push origin --tags",
        "release:major": "npm version major && npm publish",
        "release:minor": "npm version minor && npm publish",
        "release:patch": "npm version patch && npm publish",
        "release:prerelease": "npm version prerelease && npm publish --tag pegasus",
        "test": "npm run compile && npm run lint && npm run coverage && nsp check",
        "watch": "babel --watch -d lib/ src/"
    },
    "semistandard": {
        "env": [
            "mocha"
        ]
    },
    "types": [
        "./index.d.ts",
        "./client.d.ts"
    ],
    "version": "2.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
