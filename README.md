# npmdoc-identity-obj-proxy

#### api documentation for  [identity-obj-proxy (v3.0.0)](https://github.com/keyanzhang/identity-obj-proxy#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-identity-obj-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-identity-obj-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-identity-obj-proxy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-identity-obj-proxy)

#### an identity object using ES6 proxies

[![NPM](https://nodei.co/npm/identity-obj-proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/identity-obj-proxy)

- [https://npmdoc.github.io/node-npmdoc-identity-obj-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-identity-obj-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-identity-obj-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-identity-obj-proxy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-identity-obj-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-identity-obj-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Keyan Zhang",
        "url": "http://keya.nz"
    },
    "bugs": {
        "url": "https://github.com/keyanzhang/identity-obj-proxy/issues"
    },
    "dependencies": {
        "harmony-reflect": "^1.4.6"
    },
    "description": "an identity object using ES6 proxies",
    "devDependencies": {
        "babel-core": "^6.11.4",
        "babel-jest": "^14.1.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-stage-0": "^6.5.0",
        "coveralls": "^2.11.12",
        "eslint": "^3.2.2",
        "eslint-config-airbnb-base": "^5.0.1",
        "eslint-plugin-import": "^1.12.0",
        "jest-cli": "^14.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "94d2bda96084453ef36fbc5aaec37e0f79f1fc14",
        "tarball": "https://registry.npmjs.org/identity-obj-proxy/-/identity-obj-proxy-3.0.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "4a4461f921802c76835b957776600f705d1e3351",
    "homepage": "https://github.com/keyanzhang/identity-obj-proxy#readme",
    "jest": {
        "automock": false,
        "testPathDirs": [
            "<rootDir>/src"
        ]
    },
    "keywords": [
        "proxy",
        "proxies",
        "identity",
        "jest",
        "mock"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "keyanzhang"
        }
    ],
    "name": "identity-obj-proxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/keyanzhang/identity-obj-proxy.git"
    },
    "scripts": {
        "coverage": "node --harmony_proxies node_modules/.bin/jest --coverage",
        "coveralls": "npm run coverage && cat ./coverage/lcov.info | coveralls",
        "lint": "eslint src",
        "prepublish": "npm run lint && npm run test",
        "test": "node --harmony_proxies node_modules/.bin/jest"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
