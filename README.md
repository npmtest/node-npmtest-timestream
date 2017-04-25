# npmtest-timestream

#### basic test coverage for  [timestream (v0.1.1)](https://github.com/brycebaril/timestream)  [![npm package](https://img.shields.io/npm/v/npmtest-timestream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-timestream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-timestream.svg)](https://travis-ci.org/npmtest/node-npmtest-timestream)

#### A suite of tools for working with objectMode streams of time-ordered data. (e.g. tsdb records)

[![NPM](https://nodei.co/npm/timestream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/timestream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-timestream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-timestream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-timestream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-timestream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-timestream/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-timestream/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-timestream/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-timestream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-timestream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-timestream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-timestream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-timestream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-timestream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-timestream/build/test-report.html](https://npmtest.github.io/node-npmtest-timestream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-timestream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-timestream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-timestream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-timestream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-timestream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-timestream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-timestream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-timestream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bryce B. Baril"
    },
    "bugs": {
        "url": "https://github.com/brycebaril/timestream/issues"
    },
    "dependencies": {
        "stream-joins": "~0.1.5",
        "terminus": "~1.0.11",
        "timestream-aggregates": "~0.1.7",
        "timestream-filters": "~0.2.3",
        "timestream-gen": "~0.1.1",
        "timestream-ops": "~0.2.0"
    },
    "description": "A suite of tools for working with objectMode streams of time-ordered data. (e.g. tsdb records)",
    "devDependencies": {
        "stream-spigot": "~3.0.5",
        "tape": "~3.5.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "fd1b91126abb2d88e19d4b9380960006f5774080",
        "tarball": "https://registry.npmjs.org/timestream/-/timestream-0.1.1.tgz"
    },
    "gitHead": "08a59c462d1e9ede8d190a92c0ecdf597bc607b3",
    "homepage": "https://github.com/brycebaril/timestream",
    "keywords": [
        "stream",
        "tsdb",
        "timeseries"
    ],
    "license": "MIT",
    "main": "timestream.js",
    "maintainers": [
        {
            "name": "bryce"
        }
    ],
    "name": "timestream",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/brycebaril/timestream.git"
    },
    "scripts": {
        "test": "node test/"
    },
    "version": "0.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
