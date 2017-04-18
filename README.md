# npmtest-dat

#### test coverage for  [dat (v12.0.3)](https://datproject.org)  [![npm package](https://img.shields.io/npm/v/npmtest-dat.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dat) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dat.svg)](https://travis-ci.org/npmtest/node-npmtest-dat)

#### Dat is the package manager for data. Easily share and version control data.

[![NPM](https://nodei.co/npm/dat.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dat)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dat/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dat/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dat/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dat/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dat/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dat/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dat/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dat/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dat/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dat/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dat/build/test-report.html](https://npmtest.github.io/node-npmtest-dat/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dat/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dat/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dat/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dat/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "dat": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/datproject/dat/issues"
    },
    "dependencies": {
        "dat-doctor": "^1.2.3",
        "dat-encoding": "^4.0.2",
        "dat-node": "^1.4.0",
        "dat-registry": "^2.1.2",
        "debug": "^2.6.2",
        "memdb": "^1.3.1",
        "mkdirp": "^0.5.1",
        "nets": "^3.2.0",
        "pretty-bytes": "^4.0.2",
        "progress-string": "^1.2.1",
        "prompt": "^1.0.0",
        "rimraf": "^2.5.4",
        "status-logger": "^3.0.0",
        "subcommand": "^2.1.0",
        "xtend": "^4.0.1"
    },
    "description": "Dat is the package manager for data. Easily share and version control data.",
    "devDependencies": {
        "dat-land": "github:datproject/datfolder",
        "hypercore": "^4.15.1",
        "hyperdiscovery": "^1.0.1",
        "recursive-readdir-sync": "^1.0.6",
        "standard": "^9.0.1",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.3",
        "tape-spawn": "^1.4.2"
    },
    "directories": {
        "test": "tests"
    },
    "dist": {
        "shasum": "41bafebe40a7d4f9f347ae3a96afc64bd4fcd951",
        "tarball": "https://registry.npmjs.org/dat/-/dat-12.0.3.tgz"
    },
    "gitHead": "29246df27dff180092508292b087ba8529338f2e",
    "homepage": "https://datproject.org",
    "keywords": [
        "data package",
        "dataset",
        "replication",
        "distributed"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "jhand"
        },
        {
            "name": "karissa"
        },
        {
            "name": "mafintosh"
        },
        {
            "name": "maxogden"
        }
    ],
    "name": "dat",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/datproject/dat.git"
    },
    "scripts": {
        "auth-server": "DEBUG=* node scripts/auth-server.js",
        "install-precommit": "echo ./node_modules/.bin/standard > .git/hooks/pre-commit && chmod +x .git/hooks/pre-commit",
        "standard": "standard",
        "test": "standard && tape 'tests/*[!auth].js' | tap-spec"
    },
    "version": "12.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
