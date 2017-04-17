# test coverage for  [extract-text-webpack-plugin (v2.1.0)](http://github.com/webpack/extract-text-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmtest-extract-text-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-extract-text-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-extract-text-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-extract-text-webpack-plugin)
#### Extract text from bundle into a file.

[![NPM](https://nodei.co/npm/extract-text-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/extract-text-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-extract-text-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-extract-text-webpack-plugin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/test-report.html](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-extract-text-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-extract-text-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-extract-text-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-extract-text-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-extract-text-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bugs": {
        "url": "https://github.com/webpack/extract-text-webpack-plugin/issues"
    },
    "dependencies": {
        "ajv": "^4.11.2",
        "async": "^2.1.2",
        "loader-utils": "^1.0.2",
        "webpack-sources": "^0.1.0"
    },
    "description": "Extract text from bundle into a file.",
    "devDependencies": {
        "codecov.io": "^0.1.2",
        "coveralls": "^2.11.2",
        "css-loader": "^0.26.1",
        "file-loader": "^0.9.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "mocha-lcov-reporter": "1.2.0",
        "raw-loader": "^0.5.1",
        "should": "^11.1.2",
        "standard-version": "^4.0.0",
        "style-loader": "^0.13.0",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "69315b885f876dbf96d3819f6a9f1cca7aebf159",
        "tarball": "https://registry.npmjs.org/extract-text-webpack-plugin/-/extract-text-webpack-plugin-2.1.0.tgz"
    },
    "engines": {
        "node": ">=4.3.0 < 5.0.0 || >= 5.10"
    },
    "gitHead": "75cb09eed13d15cec8f974b1210920a7f249f8e2",
    "homepage": "http://github.com/webpack/extract-text-webpack-plugin",
    "license": "MIT",
    "maintainers": [
        {
            "name": "bebraw"
        },
        {
            "name": "d3viant0ne"
        },
        {
            "name": "ericclemmons"
        },
        {
            "name": "jhnns"
        },
        {
            "name": "sokra"
        },
        {
            "name": "spacek33z"
        },
        {
            "name": "thelarkinn"
        }
    ],
    "name": "extract-text-webpack-plugin",
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": "^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/webpack/extract-text-webpack-plugin.git"
    },
    "scripts": {
        "build:example": "(cd example && webpack)",
        "cover": "istanbul cover _mocha",
        "release": "standard-version",
        "test": "mocha",
        "travis": "npm run cover -- --report lcovonly"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
