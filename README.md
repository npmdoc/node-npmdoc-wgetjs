# npmdoc-wgetjs

#### api documentation for  wgetjs (v0.3.6)  [![npm package](https://img.shields.io/npm/v/npmdoc-wgetjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wgetjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wgetjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wgetjs)

#### Ultra simple async retrieval of remote files over http or https

[![NPM](https://nodei.co/npm/wgetjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wgetjs)

- [https://npmdoc.github.io/node-npmdoc-wgetjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wgetjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wgetjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wgetjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wgetjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wgetjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "wgetjs",
    "version": "0.3.6",
    "description": "Ultra simple async retrieval of remote files over http or https",
    "main": "wget.js",
    "scripts": {
        "test": "mocha -R list test/*.js",
        "TESTS.md": "mocha -R markdown test/*.js > TESTS.md"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/angleman/wgetjs.git"
    },
    "keywords": [
        "curl",
        "wget",
        "download",
        "file",
        "http",
        "https"
    ],
    "author": "angleman",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/angleman/wgetjs/issues"
    },
    "engines": {
        "node": ">=0.8.6"
    },
    "dependencies": {
        "request": "~2.27.0"
    },
    "devDependencies": {
        "license-md": "~0.2.5",
        "grunt": "~0.4.1",
        "grunt-bump": "~0.0.11",
        "grunt-license": "~0.1.4",
        "mocha": "~1.12.0",
        "should": "~1.2.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
