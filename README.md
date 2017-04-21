# npmtest-koa-webpack-dev-middleware

#### basic test coverage for  [koa-webpack-dev-middleware (v1.4.5)](http://github.com/yiminghe/koa-webpack-dev-middleware)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-webpack-dev-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-webpack-dev-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-webpack-dev-middleware.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-webpack-dev-middleware)

#### webpack dev middleware for koa

[![NPM](https://nodei.co/npm/koa-webpack-dev-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-webpack-dev-middleware)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-webpack-dev-middleware/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-webpack-dev-middleware/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-webpack-dev-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-webpack-dev-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-webpack-dev-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-webpack-dev-middleware/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-webpack-dev-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "yiminghe@gmail.com"
    },
    "babel": {
        "presets": [
            "es2015-native-generators"
        ]
    },
    "bugs": {
        "url": "http://github.com/yiminghe/koa-webpack-dev-middleware/issues"
    },
    "dependencies": {
        "webpack-dev-middleware": "^1.10.0"
    },
    "description": "webpack dev middleware for koa",
    "devDependencies": {
        "babel-cli": "^6.0.0",
        "babel-preset-es2015-native-generators": "^6.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "78e50668bb6d8c063fbc858ff2bc235b7464550d",
        "tarball": "https://registry.npmjs.org/koa-webpack-dev-middleware/-/koa-webpack-dev-middleware-1.4.5.tgz"
    },
    "engines": {
        "node": ">=6.0.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "8387e3e0911574e682c0d84ddcb1872d30d2a9f8",
    "homepage": "http://github.com/yiminghe/koa-webpack-dev-middleware",
    "keywords": [
        "koa",
        "webpack",
        "middleware"
    ],
    "licenses": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "yiminghe"
        }
    ],
    "name": "koa-webpack-dev-middleware",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yiminghe/koa-webpack-dev-middleware.git"
    },
    "scripts": {
        "compile": "babel src --out-dir lib",
        "pub": "npm run compile && npm publish && git push origin"
    },
    "version": "1.4.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
