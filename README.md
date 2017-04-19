# npmdoc-polymer-cli

#### api documentation for  [polymer-cli (v0.17.0)](https://github.com/Polymer/polymer-cli#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-polymer-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-polymer-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-polymer-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-polymer-cli)

#### A commandline tool for Polymer projects

[![NPM](https://nodei.co/npm/polymer-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/polymer-cli)

- [https://npmdoc.github.io/node-npmdoc-polymer-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-polymer-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "The Polymer Project Authors"
    },
    "bin": {
        "polymer": "bin/polymer.js"
    },
    "bugs": {
        "url": "https://github.com/Polymer/polymer-cli/issues"
    },
    "dependencies": {
        "@types/chalk": "^0.4.31",
        "@types/del": "^2.2.31",
        "@types/findup-sync": "^0.3.29",
        "@types/fs-extra": "0.0.34",
        "@types/gulp-if": "0.0.30",
        "@types/html-minifier": "^1.1.30",
        "@types/inquirer": "0.0.30",
        "@types/merge-stream": "^1.0.28",
        "@types/node": "^6.0.41",
        "@types/parse5": "^2.2.33",
        "@types/request": "0.0.32",
        "@types/temp": "^0.8.28",
        "@types/uglify-js": "^2.6.28",
        "@types/vinyl": "^1.1.29",
        "@types/vinyl-fs": "0.0.28",
        "@types/yeoman-generator": "0.0.30",
        "chalk": "^1.1.3",
        "command-line-args": "^3.0.0",
        "command-line-commands": "^1.0.3",
        "command-line-usage": "^3.0.1",
        "css-slam": "^1.1.0",
        "del": "^2.2.2",
        "dom5": "^2.0.1",
        "findup-sync": "^0.4.2",
        "fs-extra": "^1.0.0",
        "github": "^6.0.1",
        "gulp-if": "^2.0.0",
        "gunzip-maybe": "^1.3.1",
        "html-minifier": "^3.0.1",
        "inquirer": "^1.0.2",
        "merge-stream": "^1.0.0",
        "parse5": "^2.2.3",
        "plylog": "^0.4.0",
        "polylint": "^2.10.0",
        "polymer-build": "^0.4.1",
        "polyserve": "^0.13.0",
        "request": "^2.72.0",
        "resolve": "^1.1.7",
        "tar-fs": "^1.12.0",
        "temp": "^0.8.3",
        "uglify-js": "^2.7.0",
        "update-notifier": "^1.0.0",
        "vinyl": "^1.1.1",
        "vinyl-fs": "^2.4.3",
        "web-component-tester": "^5.0.0",
        "yeoman-environment": "^1.5.2",
        "yeoman-generator": "^0.23.3"
    },
    "description": "A commandline tool for Polymer projects",
    "devDependencies": {
        "bower": "^1.7.9",
        "chai": "^3.5.0",
        "depcheck": "^0.6.3",
        "gulp": "^3.9.1",
        "gulp-eslint": "^2.0.0",
        "gulp-mocha": "^3.0.1",
        "gulp-tslint": "^5.0.0",
        "gulp-typescript": "^3.0.0",
        "run-sequence": "^1.2.0",
        "sinon": "^1.17.4",
        "tslint": "^3.10.2",
        "typescript": "^2.0.3",
        "vinyl-fs-fake": "^1.1.0",
        "yeoman-assert": "^2.2.1",
        "yeoman-test": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "35e6e01fc36564fdb614ca95681bdcb0c3d82a19",
        "tarball": "https://registry.npmjs.org/polymer-cli/-/polymer-cli-0.17.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "5966eab1bf3d1957a26df9dc82e203fe8be4a675",
    "homepage": "https://github.com/Polymer/polymer-cli#readme",
    "license": "BSD-3-Clause",
    "main": "lib/polymer-cli.js",
    "maintainers": [
        {
            "name": "justinfagnani"
        },
        {
            "name": "polymer"
        }
    ],
    "name": "polymer-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Polymer/polymer-cli.git"
    },
    "scripts": {
        "build": "gulp build",
        "lint": "gulp lint",
        "prepublish": "npm run build && npm test",
        "test": "gulp lint test"
    },
    "version": "0.17.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
