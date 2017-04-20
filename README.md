# npmtest-qrcode-terminal

#### basic test coverage for  [qrcode-terminal (v0.11.0)](https://github.com/gtanner/qrcode-terminal)  [![npm package](https://img.shields.io/npm/v/npmtest-qrcode-terminal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-qrcode-terminal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-qrcode-terminal.svg)](https://travis-ci.org/npmtest/node-npmtest-qrcode-terminal)

#### QRCodes, in the terminal

[![NPM](https://nodei.co/npm/qrcode-terminal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qrcode-terminal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-qrcode-terminal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-qrcode-terminal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-qrcode-terminal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-qrcode-terminal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-qrcode-terminal/build/test-report.html](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-qrcode-terminal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qrcode-terminal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qrcode-terminal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qrcode-terminal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-qrcode-terminal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "qrcode-terminal": "./bin/qrcode-terminal.js"
    },
    "bugs": {
        "url": "https://github.com/gtanner/qrcode-terminal/issues"
    },
    "contributors": [
        {
            "name": "Gord Tanner",
            "url": "http://github.com/gtanner"
        },
        {
            "name": "Michael Brooks",
            "url": "http://github.com/mwbrooks"
        }
    ],
    "dependencies": {},
    "description": "QRCodes, in the terminal",
    "devDependencies": {
        "expect.js": "*",
        "jshint": "*",
        "mocha": "*",
        "sinon": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "ffc6c28a2fc0bfb47052b47e23f4f446a5fbdb9e",
        "tarball": "https://registry.npmjs.org/qrcode-terminal/-/qrcode-terminal-0.11.0.tgz"
    },
    "gitHead": "9b412b3052242e054b85705f5033cd15719ef7e8",
    "homepage": "https://github.com/gtanner/qrcode-terminal",
    "keywords": [
        "ansi",
        "ascii",
        "qrcode",
        "console"
    ],
    "licenses": [
        {
            "type": "Apache 2.0"
        }
    ],
    "main": "./lib/main",
    "maintainers": [
        {
            "name": "gtanner"
        },
        {
            "name": "mwbrooks"
        }
    ],
    "name": "qrcode-terminal",
    "optionalDependencies": {},
    "preferGlobal": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gtanner/qrcode-terminal.git"
    },
    "scripts": {
        "test": "./node_modules/jshint/bin/jshint lib vendor && node example/basic.js && ./node_modules/mocha/bin/mocha -R nyan"
    },
    "version": "0.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
