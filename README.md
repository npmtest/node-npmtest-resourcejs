# npmtest-resourcejs

#### basic test coverage for  [resourcejs (v1.7.0)](https://github.com/travist/resourcejs)  [![npm package](https://img.shields.io/npm/v/npmtest-resourcejs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-resourcejs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-resourcejs.svg)](https://travis-ci.org/npmtest/node-npmtest-resourcejs)

#### A simple Express library to reflect Mongoose models to a REST interface.

[![NPM](https://nodei.co/npm/resourcejs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/resourcejs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-resourcejs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-resourcejs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-resourcejs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-resourcejs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-resourcejs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-resourcejs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-resourcejs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-resourcejs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-resourcejs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-resourcejs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-resourcejs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-resourcejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-resourcejs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-resourcejs/build/test-report.html](https://npmtest.github.io/node-npmtest-resourcejs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-resourcejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-resourcejs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-resourcejs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-resourcejs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-resourcejs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-resourcejs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-resourcejs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-resourcejs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Travis Tidwell"
    },
    "bugs": {
        "url": "https://github.com/travist/resourcejs/issues"
    },
    "dependencies": {
        "composable-middleware": "^0.3.0",
        "debug": "^2.6.0",
        "express": "^4.15.2",
        "fast-json-patch": "^0.5.7",
        "lodash": "^4.17.4",
        "mongodb": "^2.2.25",
        "mongoose": "^4.9.4",
        "node-paginate-anything": "git+https://github.com/polo2ro/node-paginate-anything.git"
    },
    "description": "A simple Express library to reflect Mongoose models to a REST interface.",
    "devDependencies": {
        "async": "^2.1.4",
        "body-parser": "^1.10.2",
        "chance": "^1.0.0",
        "mocha": "^2.1.0",
        "q": "^1.4.1",
        "supertest": "^0.15.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5619df5b17730ff313baf97ad47a4bc235e1345e",
        "tarball": "https://registry.npmjs.org/resourcejs/-/resourcejs-1.7.0.tgz"
    },
    "gitHead": "851889cb360343508ff742ab3488b22a779fc513",
    "homepage": "https://github.com/travist/resourcejs",
    "keywords": [
        "Express",
        "Mongoose",
        "Node",
        "MEAN"
    ],
    "license": "MIT",
    "main": "Resource.js",
    "maintainers": [
        {
            "name": "rahatarmanahmed"
        },
        {
            "name": "randallknutson"
        },
        {
            "name": "travist"
        },
        {
            "name": "zackurben"
        }
    ],
    "name": "resourcejs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/travist/resourcejs.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/mocha test/test.js -b -t 30000"
    },
    "version": "1.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
