# npmtest-cnpm

#### basic test coverage for  [cnpm (v4.5.0)](https://github.com/cnpm/cnpm)  [![npm package](https://img.shields.io/npm/v/npmtest-cnpm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cnpm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cnpm.svg)](https://travis-ci.org/npmtest/node-npmtest-cnpm)

#### cnpm: npm client for cnpmjs.org

[![NPM](https://nodei.co/npm/cnpm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cnpm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cnpm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cnpm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cnpm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cnpm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cnpm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cnpm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cnpm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cnpm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cnpm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cnpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cnpm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cnpm/build/test-report.html](https://npmtest.github.io/node-npmtest-cnpm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cnpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cnpm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cnpm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cnpm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cnpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cnpm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cnpm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cnpm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2",
        "url": "http://fengmk2.com"
    },
    "bin": {
        "cnpm": "bin/cnpm"
    },
    "bugs": {
        "url": "https://github.com/cnpm/cnpm/issues"
    },
    "ci": {
        "version": "4, 6, 7"
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "dead_horse",
            "url": "https://github.com/dead-horse"
        },
        {
            "name": "Jakukyo Friel",
            "url": "https://github.com/weakish"
        },
        {
            "name": "Zhonglei Qiu",
            "url": "https://github.com/qiu8310"
        },
        {
            "name": "popomore",
            "url": "https://github.com/popomore"
        },
        {
            "name": "alsotang",
            "url": "https://github.com/alsotang"
        }
    ],
    "dependencies": {
        "auto-correct": "^1.0.0",
        "bagpipe": "^0.3.5",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "cross-spawn": "~0.2.8",
        "debug": "^2.2.0",
        "giturl": "^1.0.0",
        "npm": "^3.10.8",
        "npm-request": "^1.0.0",
        "npminstall": "^2.19.0",
        "open": "^0.0.5",
        "urllib": "^2.17.0"
    },
    "description": "cnpm: npm client for cnpmjs.org",
    "devDependencies": {
        "autod": "^2.7.1",
        "coffee": "^3.3.0",
        "egg-ci": "^1.1.0",
        "fs-extra": "0",
        "jshint": "2",
        "mocha": "3",
        "rimraf": "^2.5.4",
        "should": "5"
    },
    "directories": {},
    "dist": {
        "shasum": "848ee6a499af2528e199e6bde29d9c1cace564a6",
        "tarball": "https://registry.npmjs.org/cnpm/-/cnpm-4.5.0.tgz"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "b4d22d9c06cb7fe33623684ff3273185186ff2cc",
    "homepage": "https://github.com/cnpm/cnpm",
    "keywords": [
        "cnpm",
        "npm",
        "npminstall"
    ],
    "license": "MIT",
    "main": "bin/cnpm",
    "maintainers": [
        {
            "name": "alsotang"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "fengmk2"
        }
    ],
    "name": "cnpm",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/cnpm/cnpm.git",
        "web": "https://github.com/cnpm/cnpm"
    },
    "scripts": {
        "autod": "autod",
        "ci": "npm run lint && npm run test",
        "lint": "jshint .",
        "test": "mocha -t 120000 test/*.test.js"
    },
    "version": "4.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
