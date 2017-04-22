# npmtest-downpress

#### basic test coverage for  [downpress (v0.1.21)](http://downpress.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-downpress.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-downpress) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-downpress.svg)](https://travis-ci.org/npmtest/node-npmtest-downpress)

#### Downpress is simple, fast and lightweight generator of static websites.

[![NPM](https://nodei.co/npm/downpress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/downpress)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-downpress/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-downpress/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-downpress/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-downpress/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-downpress/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-downpress/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-downpress/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-downpress/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-downpress/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-downpress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-downpress/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-downpress/build/test-report.html](https://npmtest.github.io/node-npmtest-downpress/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-downpress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-downpress/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-downpress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-downpress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-downpress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-downpress/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-downpress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-downpress/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "downpress",
    "subdomain": "downpress",
    "main": "./binaries/Binary.js",
    "bin": {
        "downpress": "./binaries/Binary.js"
    },
    "homepage": "http://downpress.org/",
    "author": {
        "name": "Samuel Ondrek",
        "url": "http://github.com/ondrek/",
        "website": "http://ondrek.com",
        "blog": "http://ondrek.me",
        "twitter": "@ondrek"
    },
    "bugs": {
        "url": "https://github.com/downpress/package/issues/"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/downpress/package.git"
    },
    "description": "Downpress is simple, fast and lightweight generator of static websites.",
    "keywords": [
        "markdown",
        "static",
        "website",
        "generator",
        "downpress",
        "node",
        "javascript",
        "fast",
        "speed",
        "performance",
        "semantical",
        "blog",
        "free",
        "open",
        "mdown",
        "documentation",
        "documentation-generator",
        "docs",
        "tool",
        "project"
    ],
    "preferGlobal": true,
    "version": "0.1.21",
    "license": "Apache-2.0",
    "domains": [
        "downpress.org",
        "www.downpress.org"
    ],
    "dependencies": {
        "markdown": "0.5.0",
        "colors": "0.6.2",
        "connect": "2.14.3",
        "fs-extra": "0.8.1",
        "walk": "2.3.1",
        "filequeue": "0.5.0",
        "node-minify": "0.10.2",
        "gaze": "0.5.1"
    },
    "engines": {
        "node": "0.10.*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
