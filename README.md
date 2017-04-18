# npmtest-postcss-reporter

#### test coverage for  [postcss-reporter (v3.0.0)](https://github.com/postcss/postcss-reporter)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-reporter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-reporter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-reporter.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-reporter)

#### Log PostCSS messages in the console

[![NPM](https://nodei.co/npm/postcss-reporter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-reporter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-reporter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-reporter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-reporter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-reporter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-reporter/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-reporter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-reporter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-reporter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-reporter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-reporter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-reporter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-reporter/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-reporter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-reporter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-reporter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-reporter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-reporter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-reporter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-reporter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-reporter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-reporter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Clark",
        "url": "http://davidtheclark.com"
    },
    "bugs": {
        "url": "https://github.com/postcss/postcss-reporter/issues"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "lodash": "^4.1.0",
        "log-symbols": "^1.0.2",
        "postcss": "^5.0.0"
    },
    "description": "Log PostCSS messages in the console",
    "devDependencies": {
        "eslint": "1.3.1",
        "less": "2.7.1",
        "source-map": "0.5.6",
        "stylelint": "6.8.0",
        "tape": "4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "09ea0f37a444c5693878606e09b018ebeff7cf8f",
        "tarball": "https://registry.npmjs.org/postcss-reporter/-/postcss-reporter-3.0.0.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "ea2ff315c11e037642d8b1dc3cd0216b07df5ce3",
    "homepage": "https://github.com/postcss/postcss-reporter",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "davidtheclark"
        }
    ],
    "name": "postcss-reporter",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/postcss/postcss-reporter.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "npm run lint && tape test",
        "visual": "node test/visual.js"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
