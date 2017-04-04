# api documentation for  [greenkeeper (v4.2.1)](https://greenkeeper.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-greenkeeper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-greenkeeper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-greenkeeper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-greenkeeper)
#### Your software, up to date, all the time

[![NPM](https://nodei.co/npm/greenkeeper.png?downloads=true)](https://www.npmjs.com/package/greenkeeper)

[![apidoc](https://npmdoc.github.io/node-npmdoc-greenkeeper/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-greenkeeper_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-greenkeeper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-greenkeeper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-greenkeeper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephan Bönnemann",
        "email": "stephan@boennemann.me",
        "url": "http://boennemann.me"
    },
    "bin": {
        "greenkeeper": "src/index.js",
        "gk": "src/index.js"
    },
    "bugs": {
        "url": "https://github.com/greenkeeperio/greenkeeper/issues"
    },
    "dependencies": {
        "@greenkeeper/flags": "^3.0.1",
        "abbrev": "^1.0.7",
        "boxen": "^1.0.0",
        "chalk": "^1.1.1",
        "char-spinner": "^1.0.1",
        "cli-md": "^1.2.0",
        "github-slug": "^2.0.0",
        "hide-secrets": "^1.0.0",
        "inquirer": "^2.0.0",
        "js-yaml": "3.8.0",
        "json-preserve-indent": "^1.1.1",
        "lodash": "^4.0.0",
        "moment": "^2.16.0",
        "nerf-dart": "^1.0.0",
        "node-emoji": "^1.0.4",
        "npm-registry-client": "^7.1.0",
        "npmlog": "^4.0.0",
        "opener": "^1.4.1",
        "random-string": "^0.1.2",
        "request": "^2.67.0",
        "set-blocking": "^2.0.0",
        "update-notifier": "^1.0.2",
        "valid-url": "^1.0.9",
        "validator": "^6.1.0"
    },
    "description": "Your software, up to date, all the time",
    "devDependencies": {
        "nyc": "^10.1.0",
        "semantic-release": "^6.3.2",
        "standard": "^8.0.0",
        "tap": "^10.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "56c8c53e317839d72e0781fcb54fb23917a42052",
        "tarball": "https://registry.npmjs.org/greenkeeper/-/greenkeeper-4.2.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "src"
    ],
    "gitHead": "41391bf581f47f8773ccc99e7e8454c70511dd2b",
    "homepage": "https://greenkeeper.io",
    "license": "Apache-2.0",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "boennemann",
            "email": "stephan@boennemann.me"
        }
    ],
    "name": "greenkeeper",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/greenkeeperio/greenkeeper.git"
    },
    "scripts": {
        "posttest": "./src/index.js start",
        "pretest": "standard",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "start": "./src/index.js",
        "test": "nyc tap test/*.js"
    },
    "version": "4.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module greenkeeper](#apidoc.module.greenkeeper)



# <a name="apidoc.module.greenkeeper"></a>[module greenkeeper](#apidoc.module.greenkeeper)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
