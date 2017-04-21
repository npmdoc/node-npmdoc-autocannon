# npmdoc-autocannon

#### api documentation for  [autocannon (v0.16.5)](https://github.com/mcollina/autocannon#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-autocannon.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-autocannon) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-autocannon.svg)](https://travis-ci.org/npmdoc/node-npmdoc-autocannon)

#### Fast HTTP benchmarking tool written in Node.js

[![NPM](https://nodei.co/npm/autocannon.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/autocannon)

- [https://npmdoc.github.io/node-npmdoc-autocannon/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-autocannon/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-autocannon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-autocannon/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-autocannon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-autocannon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "autocannon",
    "version": "0.16.5",
    "description": "Fast HTTP benchmarking tool written in Node.js",
    "main": "autocannon.js",
    "bin": {
        "autocannon": "autocannon.js"
    },
    "scripts": {
        "test": "standard && tap test/*.test.js"
    },
    "pre-commit": [
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mcollina/autocannon.git"
    },
    "keywords": [
        "http",
        "soak",
        "load",
        "fast",
        "wrk",
        "ab",
        "test"
    ],
    "author": "Matteo Collina <hello@matteocollina.com>",
    "contributors": [
        "Glen Keane <glenkeane.94@gmail.com> (http://glenkeane.me/)",
        "Donald Robertson <donaldarobertson89@gmail.com"
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mcollina/autocannon/issues"
    },
    "homepage": "https://github.com/mcollina/autocannon#readme",
    "devDependencies": {
        "bl": "^1.1.2",
        "pre-commit": "^1.1.2",
        "split2": "^2.1.0",
        "standard": "^9.0.0",
        "tap": "^10.3.0"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "color-support": "^1.1.1",
        "deep-extend": "^0.4.1",
        "hdr-histogram-percentiles-obj": "^1.1.0",
        "http-parser-js": "^0.4.2",
        "hyperid": "^1.1.0",
        "minimist": "^1.2.0",
        "native-hdr-histogram": "^0.4.0",
        "pretty-bytes": "^4.0.2",
        "progress": "^1.1.8",
        "reinterval": "^1.1.0",
        "retimer": "^1.0.1",
        "table": "^4.0.1",
        "timestring": "^3.0.1",
        "xtend": "^4.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
