# npmtest-cordova-gen-icon

#### basic test coverage for  [cordova-gen-icon (v0.4.6)](https://bitbucket.org/ntakimura/cordova-gen-icon#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-gen-icon.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-gen-icon) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-gen-icon.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-gen-icon)

#### Apache Cordova Icon Generator

[![NPM](https://nodei.co/npm/cordova-gen-icon.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-gen-icon)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-gen-icon/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-gen-icon/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-gen-icon/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-gen-icon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Naoki Takimura"
    },
    "bin": {
        "cordova-gen-icon": "bin/cordova-gen-icon"
    },
    "dependencies": {
        "commander": "*",
        "dom-js": "*",
        "imagemagick": "*"
    },
    "description": "Apache Cordova Icon Generator",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": [
        "bin",
        "libs",
        "hooks"
    ],
    "dist": {
        "shasum": "86a327ee627f4255f09148294d0e87f6949613b0",
        "tarball": "https://registry.npmjs.org/cordova-gen-icon/-/cordova-gen-icon-0.4.6.tgz"
    },
    "homepage": "https://bitbucket.org/ntakimura/cordova-gen-icon#readme",
    "keywords": [
        "cordova",
        "hooks",
        "icon"
    ],
    "license": {
        "type": "WTFPL",
        "url": "http://www.wtfpl.net/about/"
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "ntakimura"
        }
    ],
    "name": "cordova-gen-icon",
    "optionalDependencies": {},
    "repository": {
        "type": "mercurial",
        "url": "git+ssh://git@bitbucket.org/ntakimura/cordova-gen-icon.git"
    },
    "scripts": {
        "jsdoc": "jsdoc -d jsdoc index.js libs/*.js",
        "test": "mocha -R spec tests/runner.js"
    },
    "version": "0.4.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
