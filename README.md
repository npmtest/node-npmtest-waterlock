# npmtest-waterlock

#### basic test coverage for  [waterlock (v0.1.0)](http://waterlock.ninja/)  [![npm package](https://img.shields.io/npm/v/npmtest-waterlock.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-waterlock) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-waterlock.svg)](https://travis-ci.org/npmtest/node-npmtest-waterlock)

#### User authentication and Json Web Tokens for Sails

[![NPM](https://nodei.co/npm/waterlock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/waterlock)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-waterlock/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-waterlock/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-waterlock/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-waterlock/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-waterlock/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-waterlock/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-waterlock/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-waterlock/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-waterlock/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-waterlock/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-waterlock/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-waterlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-waterlock/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-waterlock/build/test-report.html](https://npmtest.github.io/node-npmtest-waterlock/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-waterlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-waterlock/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-waterlock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-waterlock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-waterlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-waterlock/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-waterlock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-waterlock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Rivera"
    },
    "bin": {
        "waterlock": "./bin/waterlock.js"
    },
    "bugs": {
        "url": "https://github.com/waterlock/waterlock/issues"
    },
    "contributors": [
        {
            "name": "David Rivera"
        }
    ],
    "dependencies": {
        "commander": "~2.8.1",
        "jwt-simple": "~0.3.0",
        "lodash": "~3.7.0",
        "moment": "~2.10.2",
        "node-uuid": "~1.4.3",
        "winston": "~1.0.0"
    },
    "description": "User authentication and Json Web Tokens for Sails",
    "devDependencies": {
        "coveralls": "*",
        "istanbul": "*",
        "jshint": "*",
        "mocha": "*",
        "proxyquire": "*",
        "sails": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "33f6913bca3a4f88c0fc318e79ab2f34bc94f6ce",
        "tarball": "https://registry.npmjs.org/waterlock/-/waterlock-0.1.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "17ae7936bb65dfef9ab74da07857601e0f5baa15",
    "homepage": "http://waterlock.ninja/",
    "keywords": [
        "waterlock",
        "sails",
        "authentication",
        "json web tokens",
        "jwt"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "duhruh"
        },
        {
            "name": "globegitter"
        },
        {
            "name": "kriswill"
        }
    ],
    "name": "waterlock",
    "optionalDependencies": {},
    "preferGlobal": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/waterlock/waterlock.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "0.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
