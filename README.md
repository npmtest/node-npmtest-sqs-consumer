# test coverage for  [sqs-consumer (v3.5.0)](https://github.com/BBC/sqs-consumer)  [![npm package](https://img.shields.io/npm/v/npmtest-sqs-consumer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sqs-consumer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sqs-consumer.svg)](https://travis-ci.org/npmtest/node-npmtest-sqs-consumer)
#### Build SQS-based Node applications without the boilerplate

[![NPM](https://nodei.co/npm/sqs-consumer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sqs-consumer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sqs-consumer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sqs-consumer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sqs-consumer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sqs-consumer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sqs-consumer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sqs-consumer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sqs-consumer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sqs-consumer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sqs-consumer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sqs-consumer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sqs-consumer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sqs-consumer/build/test-report.html](https://npmtest.github.io/node-npmtest-sqs-consumer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sqs-consumer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sqs-consumer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sqs-consumer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sqs-consumer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sqs-consumer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sqs-consumer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sqs-consumer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sqs-consumer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "robin@robinmurphy.co.uk"
    },
    "bugs": {
        "url": "https://github.com/BBC/sqs-consumer/issues"
    },
    "dependencies": {
        "async": "^2.0.1",
        "aws-sdk": "^2.0.23",
        "debug": "^2.1.0"
    },
    "description": "Build SQS-based Node applications without the boilerplate",
    "devDependencies": {
        "codeclimate-test-reporter": "0.4.1",
        "istanbul": "^0.4.1",
        "jshint": "^2.9.1",
        "mocha": "^3.0.2",
        "sinon": "^1.10.3"
    },
    "directories": {},
    "dist": {
        "shasum": "483b2c261ca5c9130489dafbacba3edb29f31a7f",
        "tarball": "https://registry.npmjs.org/sqs-consumer/-/sqs-consumer-3.5.0.tgz"
    },
    "gitHead": "1e195e542623d8aff531efaa2c28f419739fa438",
    "homepage": "https://github.com/BBC/sqs-consumer",
    "jshintConfig": {
        "quotmark": "single",
        "unused": true,
        "undef": true,
        "node": true,
        "globals": {
            "describe": false,
            "it": false,
            "before": false,
            "beforeEach": false,
            "after": false,
            "afterEach": false
        }
    },
    "keywords": [
        "sqs",
        "queue",
        "consumer"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ibl"
        }
    ],
    "name": "sqs-consumer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/BBC/sqs-consumer.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha -- -R dot && open coverage/lcov-report/index.html",
        "lcov": "istanbul cover _mocha -- -R dot",
        "lint": "jshint .",
        "posttest": "npm run lint",
        "test": "mocha"
    },
    "version": "3.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
