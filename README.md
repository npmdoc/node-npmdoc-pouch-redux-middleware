# npmdoc-pouch-redux-middleware

#### api documentation for  [pouch-redux-middleware (v0.6.1)](https://github.com/pgte/pouch-redux-middleware#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-pouch-redux-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pouch-redux-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pouch-redux-middleware.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pouch-redux-middleware)

#### PouchDB Redux Middleware

[![NPM](https://nodei.co/npm/pouch-redux-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pouch-redux-middleware)

- [https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pouch-redux-middleware",
    "version": "0.6.1",
    "description": "PouchDB Redux Middleware",
    "main": "lib/index.js",
    "scripts": {
        "test": "node --harmony node_modules/istanbul/lib/cli.js cover -- lab -vl && istanbul check-coverage",
        "prepublish": "npm run build",
        "build": "babel ./src -d lib"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pgte/pouch-redux-middleware.git"
    },
    "keywords": [
        "pouchdb",
        "redux",
        "react",
        "middleware"
    ],
    "author": "pgte",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/pgte/pouch-redux-middleware/issues"
    },
    "homepage": "https://github.com/pgte/pouch-redux-middleware#readme",
    "dependencies": {
        "async-function-queue": "^1.0.0",
        "deep-equal": "^1.0.1",
        "json-path": "^0.1.3",
        "xtend": "^4.0.1"
    },
    "devDependencies": {
        "async": "^2.1.4",
        "code": "^4.0.0",
        "istanbul": "^0.4.5",
        "lab": "^12.1.0",
        "memdown": "^1.2.4",
        "pouchdb": "^6.1.2",
        "pre-commit": "^1.2.2",
        "redux": "^3.6.0",
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-stage-0": "^6.22.0"
    },
    "pre-commit": [
        "test"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
