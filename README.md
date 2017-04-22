# npmtest-asynquence

#### basic test coverage for  [asynquence (v0.10.0)](http://github.com/getify/asynquence)  [![npm package](https://img.shields.io/npm/v/npmtest-asynquence.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-asynquence) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-asynquence.svg)](https://travis-ci.org/npmtest/node-npmtest-asynquence)

#### promise-style async sequence flow-control

[![NPM](https://nodei.co/npm/asynquence.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/asynquence)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-asynquence/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-asynquence/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-asynquence/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-asynquence/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-asynquence/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-asynquence/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-asynquence/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-asynquence/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-asynquence/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-asynquence/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-asynquence/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-asynquence/build/test-report.html](https://npmtest.github.io/node-npmtest-asynquence/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-asynquence/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-asynquence/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-asynquence/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-asynquence/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-asynquence/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-asynquence/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-asynquence/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-asynquence/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Simpson"
    },
    "bugs": {
        "url": "https://github.com/getify/asynquence/issues"
    },
    "dependencies": {},
    "description": "promise-style async sequence flow-control",
    "devDependencies": {
        "babel-core": "~5.8.12",
        "es-feature-tests": "latest",
        "native-promise-only": "latest",
        "uglify-js": "~2.4.24"
    },
    "directories": {},
    "dist": {
        "shasum": "4ec766a3876016ec3d14f7ba834f660d589f7c31",
        "tarball": "https://registry.npmjs.org/asynquence/-/asynquence-0.10.0.tgz"
    },
    "gitHead": "54a7afae5bf118b5d1af9bf482b46f5428d3d580",
    "homepage": "http://github.com/getify/asynquence",
    "keywords": [
        "async",
        "flow-control",
        "sequences",
        "promise",
        "iterator",
        "generator"
    ],
    "license": "MIT",
    "main": "./asq.src.js",
    "maintainers": [
        {
            "name": "getify"
        }
    ],
    "name": "asynquence",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/getify/asynquence.git"
    },
    "scripts": {
        "build": "npm run build-core",
        "build-core": "./build-core.js",
        "prepublish": "npm run build-core",
        "test": "./node-tests.js"
    },
    "version": "0.10.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
