# npmtest-jdf

#### basic test coverage for  [jdf (v2.1.41)](https://github.com/putaoshu/jdf)  [![npm package](https://img.shields.io/npm/v/npmtest-jdf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jdf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jdf.svg)](https://travis-ci.org/npmtest/node-npmtest-jdf)

#### 京东前端开发集成解决方案

[![NPM](https://nodei.co/npm/jdf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jdf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jdf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jdf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jdf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jdf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jdf/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jdf/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jdf/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jdf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jdf/tree/gh-pages/build)|

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
    "author": {
        "name": "jdf"
    },
    "bin": {
        "jdf": "bin/jdf"
    },
    "bugs": {
        "url": "http://github.com/putaoshu/jdf/issues"
    },
    "dependencies": {
        "async": "2.1.4",
        "atropa-jslint": "0.1.2",
        "autoprefixer": "6.5.3",
        "babel-core": "6.18.2",
        "babel-preset-es2015": "6.18.0",
        "babel-preset-stage-1": "6.16.0",
        "browser-sync": "2.18.2",
        "clean-css": "2.1.8",
        "colors": "1.0.2",
        "commander": "2.9.0",
        "csslint": "0.10.0",
        "cssnext": "1.8.4",
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
        "node-sass": "4.1.1",
        "node-watch": "0.4.1",
        "postcss": "5.2.6",
        "q": "1.0.1",
        "qrcode-terminal": "0.11.0",
        "requirejs": "2.3.2",
        "simple-prompt": "0.2.1",
        "sync-request": "4.0.1",
        "tar": "0.1.19",
        "uglify-js": "2.7.5",
        "update-notifier": "2.1.0",
        "velocityjs": "0.4.3",
        "webp-converter": "2.1.4"
    },
    "description": "京东前端开发集成解决方案",
    "devDependencies": {
        "expect.js": "^0.3.1",
        "mocha": "3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3a92bb8c83ba3b10e6ac757ec7899fd8decc8817",
        "tarball": "https://registry.npmjs.org/jdf/-/jdf-2.1.41.tgz"
    },
    "engines": {
        "node": ">= 4.2.6"
    },
    "gitHead": "09d156aa7ad305b8f3af5eb55ebfdff780e02bd4",
    "homepage": "https://github.com/putaoshu/jdf",
    "keywords": [
        "jdf"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "putaoshu"
        },
        {
            "name": "wshxbqq"
        }
    ],
    "name": "jdf",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/putaoshu/jdf.git"
    },
    "scripts": {
        "test": "mocha test/index.js"
    },
    "version": "2.1.41"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
