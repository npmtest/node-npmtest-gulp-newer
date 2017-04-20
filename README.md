# npmtest-gulp-newer

#### basic test coverage for  [gulp-newer (v1.3.0)](https://github.com/tschaub/gulp-newer)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-newer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-newer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-newer.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-newer)

#### Only pass through newer source files

[![NPM](https://nodei.co/npm/gulp-newer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-newer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-newer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-newer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-newer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-newer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-newer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-newer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-newer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-newer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-newer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-newer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-newer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-newer/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-newer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-newer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-newer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-newer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-newer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-newer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-newer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-newer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-newer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Schaub",
        "url": "http://tschaub.net/"
    },
    "bugs": {
        "url": "https://github.com/tschaub/gulp-newer/issues"
    },
    "dependencies": {
        "glob": "^7.0.3",
        "gulp-util": "^3.0.7",
        "kew": "^0.7.0"
    },
    "description": "Only pass through newer source files",
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.7.1",
        "eslint-config-tschaub": "^6.0.0",
        "gulp": "^3.9.1",
        "mocha": "^3.1.0",
        "mock-fs": "^3.11.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d50ecacbb822eda492b57324a6c85a07fd9a55c1",
        "tarball": "https://registry.npmjs.org/gulp-newer/-/gulp-newer-1.3.0.tgz"
    },
    "eslintConfig": {
        "extends": "tschaub"
    },
    "gitHead": "7e41955b90d00c7a5848bdc0d21cc27072a60d35",
    "homepage": "https://github.com/tschaub/gulp-newer",
    "keywords": [
        "gulp",
        "gulpplugin",
        "newer",
        "mtime"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "tschaub"
        }
    ],
    "name": "gulp-newer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/tschaub/gulp-newer.git"
    },
    "scripts": {
        "pretest": "eslint index.js spec.js",
        "test": "mocha spec.js"
    },
    "version": "1.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
