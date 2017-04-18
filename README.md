# npmtest-osa

#### test coverage for  [osa (v2.5.0)](https://github.com/brandonhorst/node-osa)  [![npm package](https://img.shields.io/npm/v/npmtest-osa.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-osa) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-osa.svg)](https://travis-ci.org/npmtest/node-npmtest-osa)

#### node.js module for interfacing with OSX 10.10 Javascript OSA Scripting

[![NPM](https://nodei.co/npm/osa.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/osa)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-osa/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-osa/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-osa/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-osa/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-osa/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-osa/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-osa/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-osa/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-osa/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-osa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-osa/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-osa/build/test-report.html](https://npmtest.github.io/node-npmtest-osa/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-osa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-osa/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-osa/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-osa/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-osa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-osa/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-osa/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-osa/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "@brandonhorst"
    },
    "bugs": {
        "url": "https://github.com/brandonhorst/node-osa/issues"
    },
    "dependencies": {},
    "description": "node.js module for interfacing with OSX 10.10 Javascript OSA Scripting",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.14",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.2",
        "semistandard": "^9.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b2eadd42d1bd2f20afea2b1305bb31ed2d4b3754",
        "tarball": "https://registry.npmjs.org/osa/-/osa-2.5.0.tgz"
    },
    "gitHead": "db17b0d2db74bec8de2b2c7fa83fb02e74d0b6ca",
    "homepage": "https://github.com/brandonhorst/node-osa",
    "keywords": [
        "osa",
        "osx",
        "yosemite",
        "applescript",
        "osascript",
        "automation",
        "mac"
    ],
    "license": "MIT",
    "main": "lib/osa.js",
    "maintainers": [
        {
            "name": "brandonhorst"
        }
    ],
    "name": "osa",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/brandonhorst/node-osa.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/mocha/bin/_mocha -- -u exports -R spec",
        "demo": "node demo/demo.js",
        "lint": "semistandard",
        "test": "mocha test"
    },
    "version": "2.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
