# npmtest-sax

#### test coverage for  [sax (v1.2.2)](https://github.com/isaacs/sax-js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sax.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sax) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sax.svg)](https://travis-ci.org/npmtest/node-npmtest-sax)

#### An evented streaming XML parser in JavaScript

[![NPM](https://nodei.co/npm/sax.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sax)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sax/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sax/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sax/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sax/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sax/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sax/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sax/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sax/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sax/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sax/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sax/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sax/build/test-report.html](https://npmtest.github.io/node-npmtest-sax/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sax/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sax/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sax/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sax/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sax/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sax/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sax/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sax/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter",
        "url": "http://blog.izs.me/"
    },
    "bugs": {
        "url": "https://github.com/isaacs/sax-js/issues"
    },
    "contributors": [
        {
            "name": "Isaac Z. Schlueter"
        },
        {
            "name": "Stein Martin Hustad"
        },
        {
            "name": "Mikeal Rogers"
        },
        {
            "name": "Laurie Harper"
        },
        {
            "name": "Jann Horn"
        },
        {
            "name": "Elijah Insua"
        },
        {
            "name": "Henry Rawas"
        },
        {
            "name": "Justin Makeig"
        },
        {
            "name": "Mike Schilling"
        }
    ],
    "dependencies": {},
    "description": "An evented streaming XML parser in JavaScript",
    "devDependencies": {
        "standard": "^8.6.0",
        "tap": "^10.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "fd8631a23bc7826bef5d871bdb87378c95647828",
        "tarball": "https://registry.npmjs.org/sax/-/sax-1.2.2.tgz"
    },
    "files": [
        "lib/sax.js",
        "LICENSE",
        "README.md"
    ],
    "gitHead": "27a70c4af4980323d8af47483a126289ea32e567",
    "homepage": "https://github.com/isaacs/sax-js#readme",
    "license": "ISC",
    "main": "lib/sax.js",
    "maintainers": [
        {
            "name": "isaacs"
        }
    ],
    "name": "sax",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/isaacs/sax-js.git"
    },
    "scripts": {
        "posttest": "standard -F test/*.js lib/*.js",
        "test": "tap test/*.js --cov -j4"
    },
    "version": "1.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
