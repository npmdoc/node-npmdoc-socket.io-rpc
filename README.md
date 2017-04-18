# npmdoc-socket.io-rpc

#### api documentation for  [socket.io-rpc (v1.1.3)](https://github.com/capaj/socket.io-rpc#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-socket.io-rpc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-socket.io-rpc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-socket.io-rpc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-socket.io-rpc)

#### Minimalistic remote procedure call(RPC/RMI) library bootstrapped on socket.io

[![NPM](https://nodei.co/npm/socket.io-rpc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/socket.io-rpc)

- [https://npmdoc.github.io/node-npmdoc-socket.io-rpc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-socket.io-rpc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-socket.io-rpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-socket.io-rpc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-socket.io-rpc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-socket.io-rpc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "capaj"
    },
    "bugs": {
        "url": "https://github.com/capaj/socket.io-rpc/issues"
    },
    "dependencies": {
        "co": "^4.6.0",
        "debug": "^2.2",
        "o.extend": "^1.0.1",
        "serialize-error": "^1.1.0",
        "socket.io": "^1.4",
        "traverse": "^0.6.6"
    },
    "description": "Minimalistic remote procedure call(RPC/RMI) library bootstrapped on socket.io",
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^2.4.5",
        "socket.io-rpc-client": "^1.1.3",
        "standard": "^6.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "fc20d22686058223da5a14302c96a182309780dd",
        "tarball": "https://registry.npmjs.org/socket.io-rpc/-/socket.io-rpc-1.1.3.tgz"
    },
    "engines": {
        "node": ">0.12.0"
    },
    "gitHead": "5d14d85242035f640512e83c9ef326a4225d0e38",
    "homepage": "https://github.com/capaj/socket.io-rpc#readme",
    "keywords": [
        "socket.io",
        "rpc",
        "isomorphic",
        "rmi"
    ],
    "license": "MIT",
    "main": "./main.js",
    "maintainers": [
        {
            "name": "capaj"
        }
    ],
    "name": "socket.io-rpc",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/capaj/socket.io-rpc.git"
    },
    "scripts": {
        "install_example": "cd simple-example && npm install && jspm install",
        "precommit": "npm test",
        "pretest": "standard",
        "test": "mocha"
    },
    "standard": {
        "ignore": [
            "simple-example/**",
            "console-shim.js"
        ]
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
