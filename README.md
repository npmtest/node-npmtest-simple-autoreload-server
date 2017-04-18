# npmtest-simple-autoreload-server

#### test coverage for  [simple-autoreload-server (v0.2.6)](https://github.com/cytb/simple-autoreload-server)  [![npm package](https://img.shields.io/npm/v/npmtest-simple-autoreload-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-simple-autoreload-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-simple-autoreload-server.svg)](https://travis-ci.org/npmtest/node-npmtest-simple-autoreload-server)

#### Simple Web Server with live/autoreload features without browser extensions.

[![NPM](https://nodei.co/npm/simple-autoreload-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/simple-autoreload-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-simple-autoreload-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-simple-autoreload-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-simple-autoreload-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/test-report.html](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-simple-autoreload-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-simple-autoreload-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-simple-autoreload-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-simple-autoreload-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-simple-autoreload-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "cytb",
        "url": "https://github.com/cytb/"
    },
    "bin": {
        "autoreload-server": "bin/autoreload"
    },
    "bugs": {
        "url": "https://github.com/cytb/simple-autoreload-server/issues"
    },
    "dependencies": {
        "colors": "0.6.2",
        "connect": "2.13.1",
        "faye-websocket": "0.9.2",
        "minimatch": "3.0.2",
        "opener": "1.4.1"
    },
    "description": "Simple Web Server with live/autoreload features without browser extensions.",
    "devDependencies": {
        "chai": "3.5.0",
        "del": "2.2.0",
        "es6-map": "0.1.4",
        "es6-promise": "4.0.5",
        "gulp": "3.9.1",
        "gulp-chmod": "1.3.0",
        "gulp-concat": "2.6.0",
        "gulp-if": "2.0.0",
        "gulp-insert": "0.5.0",
        "gulp-livescript": "3.0.0",
        "gulp-rename": "1.2.2",
        "gulp-spawn-mocha": "3.1.0",
        "gulp-template": "3.1.0",
        "gulp-uglify": "1.5.3",
        "harmony-reflect": "1.4.2",
        "livescript": "1.4.0",
        "lodash": "4.5.1",
        "mocha": "3.1.2",
        "phantom": "2.1.21",
        "phantomjs-prebuilt": "2.1.13",
        "prelude-ls": "1.0.3",
        "run-sequence": "1.1.5"
    },
    "directories": {},
    "dist": {
        "shasum": "a9857081237a5ad5cc4115258d485c6865d91318",
        "tarball": "https://registry.npmjs.org/simple-autoreload-server/-/simple-autoreload-server-0.2.6.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "379532fe9df24e5a268ac36d73888bb7b91a17ec",
    "homepage": "https://github.com/cytb/simple-autoreload-server",
    "keywords": [
        "autoreload",
        "websocket",
        "livereload",
        "web",
        "development",
        "app"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "cytb"
        }
    ],
    "name": "simple-autoreload-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/cytb/simple-autoreload-server.git"
    },
    "scripts": {
        "postversion": "git tag -f alpha && git push && git push --delete origin alpha && git push --tags",
        "prepublish": "gulp release-npm && npm prune",
        "test": "gulp test",
        "version": "gulp npm-version && git add -A"
    },
    "version": "0.2.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
