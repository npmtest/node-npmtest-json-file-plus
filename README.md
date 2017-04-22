# npmtest-json-file-plus

#### basic test coverage for  [json-file-plus (v3.3.0)](https://github.com/ljharb/json-file-plus#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-json-file-plus.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-json-file-plus) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-json-file-plus.svg)](https://travis-ci.org/npmtest/node-npmtest-json-file-plus)

#### Read from and write to a JSON file, minimizing diffs and preserving formatting.

[![NPM](https://nodei.co/npm/json-file-plus.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-file-plus)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-json-file-plus/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-file-plus/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-json-file-plus/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-json-file-plus/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-json-file-plus/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-json-file-plus/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-json-file-plus/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-json-file-plus/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-json-file-plus/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-file-plus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-json-file-plus/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-json-file-plus/build/test-report.html](https://npmtest.github.io/node-npmtest-json-file-plus/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-json-file-plus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-json-file-plus/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-json-file-plus/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-file-plus/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-json-file-plus/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-json-file-plus/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jordan Harband",
        "url": "http://ljharb.codes"
    },
    "bugs": {
        "url": "https://github.com/ljharb/json-file-plus/issues"
    },
    "contributors": [
        {
            "name": "Jordan Harband",
            "url": "http://ljharb.codes"
        }
    ],
    "dependencies": {
        "is": "^3.1.0",
        "node.extend": "^1.1.5",
        "promiseback": "^2.0.2"
    },
    "description": "Read from and write to a JSON file, minimizing diffs and preserving formatting.",
    "devDependencies": {
        "@ljharb/eslint-config": "^2.1.1",
        "covert": "^1.1.0",
        "eslint": "^2.4.0",
        "evalmd": "^0.0.16",
        "foreach": "^2.0.5",
        "jscs": "^2.11.0",
        "nsp": "^2.2.1",
        "object-keys": "^1.0.9",
        "tape": "^4.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "702a0bcaff6d85c0edbe1cd03c88a582532f99f5",
        "tarball": "https://registry.npmjs.org/json-file-plus/-/json-file-plus-3.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.4"
    },
    "gitHead": "a2156788085402c0594fd9f6bdc04fe37ccc1c6b",
    "homepage": "https://github.com/ljharb/json-file-plus#readme",
    "keywords": [
        "json",
        "json file",
        "formatting",
        "read",
        "write",
        "promise",
        "promiseback"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ljharb"
        }
    ],
    "name": "json-file-plus",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ljharb/json-file-plus.git"
    },
    "scripts": {
        "coverage": "covert test/test.js",
        "coverage-quiet": "covert test/test.js --quiet",
        "eslint": "eslint *.js test/*.js",
        "jscs": "jscs *.js test/*.js",
        "lint": "npm run jscs && npm run eslint",
        "posttest": "npm run --silent security",
        "pretest": "npm run --silent lint && evalmd README.md",
        "security": "nsp check",
        "test": "npm run tests-only",
        "tests-only": "node test/test.js"
    },
    "version": "3.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
