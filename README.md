# npmdoc-calipers

#### basic api documentation for  [calipers (v2.0.0)](https://github.com/calipersjs/calipers)  [![npm package](https://img.shields.io/npm/v/npmdoc-calipers.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-calipers) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-calipers.svg)](https://travis-ci.org/npmdoc/node-npmdoc-calipers)

#### The fastest Node.js library for measuring image and PDF dimensions.

[![NPM](https://nodei.co/npm/calipers.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/calipers)

- [https://npmdoc.github.io/node-npmdoc-calipers/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-calipers/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-calipers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-calipers/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-calipers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-calipers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marcus Gartner"
    },
    "bugs": {
        "url": "https://github.com/calipersjs/calipers/issues"
    },
    "dependencies": {
        "bluebird": "3.x.x"
    },
    "description": "The fastest Node.js library for measuring image and PDF dimensions.",
    "devDependencies": {
        "calipers-png": "2.x.x",
        "chai": "2.x.x",
        "chai-as-promised": "4.x.x",
        "coveralls": "2.x.x",
        "eslint": "1.x.x",
        "eslint-config-lob": "1.x.x",
        "istanbul": "0.x.x",
        "mocha": "2.x.x",
        "mocha-lcov-reporter": "0.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "bdf221c6a62f603b8ddd9340cacd9c79c1a03fce",
        "tarball": "https://registry.npmjs.org/calipers/-/calipers-2.0.0.tgz"
    },
    "gitHead": "235faae814bef04c879078a85ffa58650e512fe8",
    "homepage": "https://github.com/calipersjs/calipers",
    "keywords": [
        "image",
        "size",
        "pdf",
        "png",
        "jpeg",
        "gif",
        "bmp",
        "svg",
        "webp"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "mgartner"
        },
        {
            "name": "lob"
        }
    ],
    "name": "calipers",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/calipersjs/calipers.git"
    },
    "scripts": {
        "enforce": "istanbul check-coverage --statement 100 --branch 100 --function 100 --lines 100",
        "lint": "eslint .",
        "test": "NODE_ENV=test istanbul cover _mocha -- test --recursive --timeout 15000"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
