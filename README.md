# npmtest-jdf

#### basic test coverage for  [jdf (v2.1.40)](https://github.com/putaoshu/jdf)  [![npm package](https://img.shields.io/npm/v/npmtest-jdf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jdf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jdf.svg)](https://travis-ci.org/npmtest/node-npmtest-jdf)

#### 京东前端开发集成解决方案

[![NPM](https://nodei.co/npm/jdf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jdf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jdf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jdf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jdf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jdf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jdf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jdf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jdf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jdf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jdf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jdf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jdf/build/test-report.html](https://npmtest.github.io/node-npmtest-jdf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jdf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jdf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jdf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jdf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jdf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jdf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jdf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jdf",
    "description": "京东前端开发集成解决方案",
    "version": "2.1.40",
    "author": {
        "name": "jdf"
    },
    "homepage": "https://github.com/putaoshu/jdf",
    "keywords": [
        "jdf"
    ],
    "license": "MIT",
    "bin": {
        "jdf": "bin/jdf"
    },
    "engines": {
        "node": ">= 4.2.6 <= 6.9.4"
    },
    "main": "index.js",
    "scripts": {
        "test": "mocha test/jdf_output.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/putaoshu/jdf.git"
    },
    "bugs": {
        "url": "http://github.com/putaoshu/jdf/issues"
    },
    "preferGlobal": true,
    "readmeFilename": "README.md",
    "dependencies": {
        "atropa-jslint": "0.1.2",
        "clean-css": "2.1.8",
        "colors": "1.0.2",
        "csslint": "0.10.0",
        "expect.js": "0.3.1",
        "ftp": "0.3.6",
        "html-minifier": "0.6.9",
        "htmllint": "0.0.7",
        "iconv-lite": "0.4.13",
        "jdf-images": "1.1.0",
        "jdf-png-native": "1.1.0",
        "jdf-ws": "1.0.3",
        "js-beautify": "1.5.4",
        "jsmart": "2.14.0",
        "less": "2.7.1",
        "node-watch": "0.4.1",
        "q": "1.0.1",
        "requirejs": "2.3.2",
        "simple-prompt": "0.2.1",
        "tar": "0.1.19",
        "velocityjs": "0.4.3",
        "webp-converter": "2.1.4",
        "babel-core": "6.18.2",
        "babel-preset-es2015": "6.18.0",
        "babel-preset-stage-1": "6.16.0",
        "async": "2.1.4",
        "autoprefixer": "6.5.3",
        "postcss": "5.2.6",
        "cssnext": "1.8.4",
        "commander": "2.9.0",
        "browser-sync": "2.18.2",
        "qrcode-terminal": "0.11.0",
        "node-sass": "4.1.1",
        "uglify-js": "2.7.5",
        "sync-request": "4.0.1",
        "update-notifier": "2.1.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
