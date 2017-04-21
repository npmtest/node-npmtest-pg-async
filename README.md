# npmtest-pg-async

#### basic test coverage for  [pg-async (v2.4.3)](https://github.com/langpavel/node-pg-async#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pg-async.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pg-async) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pg-async.svg)](https://travis-ci.org/npmtest/node-npmtest-pg-async)

#### PostgreSQL client for node.js designed for usage with ES7 async/await based on node-postgres (pg) module

[![NPM](https://nodei.co/npm/pg-async.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pg-async)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pg-async/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg-async/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pg-async/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pg-async/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pg-async/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pg-async/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pg-async/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pg-async/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pg-async/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pg-async/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pg-async/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pg-async/build/test-report.html](https://npmtest.github.io/node-npmtest-pg-async/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pg-async/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pg-async/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pg-async/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pg-async/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pg-async/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pg-async/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pg-async/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pg-async/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pg-async",
    "version": "2.4.3",
    "description": "PostgreSQL client for node.js designed for usage with ES7 async/await based on node-postgres (pg) module",
    "main": "lib/index.js",
    "scripts": {
        "test": "gulp test",
        "lint": "gulp eslint"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/langpavel/node-pg-async.git"
    },
    "keywords": [
        "pg",
        "postgre",
        "postgres",
        "postgreSQL",
        "libpq",
        "database",
        "rdbms",
        "async",
        "await",
        "async-await",
        "promise",
        "bluebird",
        "babel",
        "ES6",
        "ES7"
    ],
    "author": "Pavel Lang <langpavel@phpskelet.org> (https://github.com/langpavel)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/langpavel/node-pg-async/issues"
    },
    "homepage": "https://github.com/langpavel/node-pg-async#readme",
    "dependencies": {
        "bluebird": "^3.4.6",
        "debug": "^2.3.2",
        "pg": "^6.1.0"
    },
    "devDependencies": {
        "babel": "^6.5.2",
        "babel-core": "^6.7.7",
        "babel-eslint": "^7.1.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015-node5": "^1.2.0",
        "babel-preset-stage-1": "^6.5.0",
        "babel-register": "^6.7.2",
        "chai": "^3.5.0",
        "del": "^2.2.0",
        "eslint": "^3.1.1",
        "eslint-config-strict": "^10.0.3",
        "eslint-plugin-import": "^1.4.0",
        "estraverse-fb": "^1.3.1",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-babel-istanbul": "^1.0.0",
        "gulp-eslint": "^3.0.1",
        "gulp-mocha": "^3.0.0",
        "mocha": "^3.0.0",
        "pg-native": "^1.10.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
