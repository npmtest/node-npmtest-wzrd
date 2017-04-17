# test coverage for  [wzrd (v1.5.0)](https://github.com/maxogden/wzrd)  [![npm package](https://img.shields.io/npm/v/npmtest-wzrd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wzrd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wzrd.svg)](https://travis-ci.org/npmtest/node-npmtest-wzrd)
#### Super minimal browserify development server. Inspired by [beefy](http://npmjs.org/beefy) but with less magic

[![NPM](https://nodei.co/npm/wzrd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wzrd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wzrd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wzrd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wzrd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wzrd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wzrd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wzrd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wzrd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wzrd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wzrd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wzrd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wzrd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wzrd/build/test-report.html](https://npmtest.github.io/node-npmtest-wzrd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wzrd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wzrd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wzrd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wzrd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wzrd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wzrd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wzrd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wzrd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "wzrd": "bin.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/wzrd/issues"
    },
    "dependencies": {
        "concat-stream": "^1.4.7",
        "ecstatic": "^1.4.1",
        "minimist": "^1.1.0",
        "npm-execspawn": "^1.0.6",
        "pem": "^1.4.4",
        "portfinder": "^0.4.0",
        "routes-router": "^4.1.1"
    },
    "description": "Super minimal browserify development server. Inspired by [beefy](http://npmjs.org/beefy) but with less magic",
    "devDependencies": {
        "request": "^2.51.0",
        "standard": "^7.1.2",
        "tape": "^3.0.3",
        "through2": "^0.6.3",
        "tree-kill": "0.0.6",
        "win-spawn": "^2.0.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "9694a5cd9a934dcb0a8c8e1adcaabe03fa259dd3",
        "tarball": "https://registry.npmjs.org/wzrd/-/wzrd-1.5.0.tgz"
    },
    "gitHead": "30781cf9548e5773809a30c3150096c2c906583c",
    "homepage": "https://github.com/maxogden/wzrd",
    "keywords": [
        "browserify",
        "beefy"
    ],
    "license": "BSD",
    "main": "index.js",
    "maintainers": [
        {
            "name": "maxogden"
        },
        {
            "name": "mafintosh"
        }
    ],
    "name": "wzrd",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/maxogden/wzrd.git"
    },
    "scripts": {
        "test": "standard && node test/index.js"
    },
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
