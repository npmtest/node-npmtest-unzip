# test coverage for  [unzip (v0.1.11)](https://github.com/EvanOxfeld/node-unzip)  [![npm package](https://img.shields.io/npm/v/npmtest-unzip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-unzip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-unzip.svg)](https://travis-ci.org/npmtest/node-npmtest-unzip)
#### Unzip cross-platform streaming API compatible with fstream and fs.ReadStream

[![NPM](https://nodei.co/npm/unzip.png?downloads=true)](https://www.npmjs.com/package/unzip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-unzip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-unzip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-unzip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-unzip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-unzip/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-unzip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-unzip/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-unzip/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-unzip/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-unzip/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-unzip%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-unzip/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-unzip/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-unzip%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-unzip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-unzip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-unzip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan Oxfeld",
        "email": "eoxfeld@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/EvanOxfeld/node-unzip/issues"
    },
    "dependencies": {
        "binary": ">= 0.3.0 < 1",
        "fstream": ">= 0.1.30 < 1",
        "match-stream": ">= 0.0.2 < 1",
        "pullstream": ">= 0.4.1 < 1",
        "readable-stream": "~1.0.31",
        "setimmediate": ">= 1.0.1 < 2"
    },
    "description": "Unzip cross-platform streaming API compatible with fstream and fs.ReadStream",
    "devDependencies": {
        "dirdiff": ">= 0.0.1 < 1",
        "stream-buffers": ">= 0.2.5 < 1",
        "tap": ">= 0.3.0 < 1",
        "temp": ">= 0.4.0 < 1"
    },
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "dist": {
        "shasum": "89749c63b058d7d90d619f86b98aa1535d3b97f0",
        "tarball": "https://registry.npmjs.org/unzip/-/unzip-0.1.11.tgz"
    },
    "gitHead": "5a62ecbcef6523708bb8b37decaf6e41728ac7fc",
    "homepage": "https://github.com/EvanOxfeld/node-unzip",
    "keywords": [
        "zip",
        "unzip",
        "zlib",
        "uncompress",
        "archive",
        "stream",
        "extract"
    ],
    "license": "MIT",
    "main": "unzip.js",
    "maintainers": [
        {
            "name": "evanoxfeld",
            "email": "eoxfeld@gmail.com"
        },
        {
            "name": "joeferner",
            "email": "joe@fernsroth.com"
        }
    ],
    "name": "unzip",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/EvanOxfeld/node-unzip.git"
    },
    "scripts": {
        "test": "tap ./test/*.js"
    },
    "version": "0.1.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
