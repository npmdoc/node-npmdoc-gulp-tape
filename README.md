# npmdoc-gulp-tape

#### api documentation for  [gulp-tape (v0.0.9)](https://github.com/yuanqing/gulp-tape#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-tape.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-tape) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-tape.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-tape)

#### Run Tape tests in Gulp.

[![NPM](https://nodei.co/npm/gulp-tape.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-tape)

- [https://npmdoc.github.io/node-npmdoc-gulp-tape/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-tape/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lim Yuan Qing"
    },
    "bugs": {
        "url": "https://github.com/yuanqing/gulp-tape/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.7",
        "require-uncached": "^1.0.2",
        "through2": "^2.0.0"
    },
    "description": "Run Tape tests in Gulp.",
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-istanbul": "^0.10.2",
        "gulp-util": "^3.0.7",
        "jshint": "^2.8.0",
        "tap-colorize": "^1.2.0",
        "tape": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "959671f98c2e1b39a106bb382c40e2dfb4789d32",
        "tarball": "https://registry.npmjs.org/gulp-tape/-/gulp-tape-0.0.9.tgz"
    },
    "gitHead": "eac096b82ce4b22832c97c6f6e30fb83860f9366",
    "homepage": "https://github.com/yuanqing/gulp-tape#readme",
    "keywords": [
        "gulpplugin",
        "tape",
        "test"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "yuanqing"
        },
        {
            "name": "zoubin"
        }
    ],
    "name": "gulp-tape",
    "optionalDependencies": {},
    "peerDependencies": {
        "tape": "*"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/yuanqing/gulp-tape.git"
    },
    "scripts": {
        "build": "npm run lint && npm test",
        "lint": "jshint --verbose index.js",
        "test": "gulp --cwd test test && gulp --cwd test istanbul"
    },
    "version": "0.0.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
