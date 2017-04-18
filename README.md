# npmdoc-tar.gz

#### api documentation for  [tar.gz (v1.0.5)](https://github.com/alanhoff/node-tar.gz#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-tar.gz.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-tar.gz) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-tar.gz.svg)](https://travis-ci.org/npmdoc/node-npmdoc-tar.gz)

#### Pure javascript tarball tools for Node.js

[![NPM](https://nodei.co/npm/tar.gz.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tar.gz)

- [https://npmdoc.github.io/node-npmdoc-tar.gz/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tar.gz/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tar.gz/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tar.gz/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-tar.gz/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-tar.gz/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alan Hoffmeister"
    },
    "bin": {
        "targz": "bin/targz"
    },
    "bugs": {
        "url": "https://github.com/alanhoff/node-tar.gz/issues"
    },
    "dependencies": {
        "bluebird": "^2.9.34",
        "commander": "^2.8.1",
        "fstream": "^1.0.8",
        "mout": "^0.11.0",
        "tar": "^2.1.1"
    },
    "description": "Pure javascript tarball tools for Node.js",
    "devDependencies": {
        "chai": "^3.2.0",
        "coveralls": "^2.11.3",
        "istanbul": "^0.3.17",
        "mocha": "^2.2.5",
        "temp": "^0.8.3"
    },
    "directories": {},
    "dist": {
        "shasum": "e1ada7e45ef2241b4b1ee58123c8f40b5d3c1bc4",
        "tarball": "https://registry.npmjs.org/tar.gz/-/tar.gz-1.0.5.tgz"
    },
    "gitHead": "fc231e6ded92dc03e659c5383365a6a24f818f09",
    "homepage": "https://github.com/alanhoff/node-tar.gz#readme",
    "keywords": [
        "compression",
        "decompression",
        "compress",
        "decompress",
        "tar",
        "tape",
        "archive",
        "tape",
        "arquive",
        "gzip",
        "gz",
        "tarball"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "alanhoff"
        }
    ],
    "name": "tar.gz",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/alanhoff/node-tar.gz.git"
    },
    "scripts": {
        "test": "mocha --tdd --bail test/**/*-test.js",
        "travis": "istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- -R spec test/**/*-test.js && cat ./coverage/lcov.info | ./node_modules/.bin/coveralls && rm -rf ./coverage"
    },
    "version": "1.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
