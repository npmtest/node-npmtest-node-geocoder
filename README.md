# npmtest-node-geocoder

#### basic test coverage for  [node-geocoder (v3.16.0)](https://github.com/nchaulet/node-geocoder#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-geocoder.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-geocoder) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-geocoder.svg)](https://travis-ci.org/npmtest/node-npmtest-node-geocoder)

#### Node Geocoder, node geocoding library, supports google maps, mapquest, open street map, tom tom, promise

[![NPM](https://nodei.co/npm/node-geocoder.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-geocoder)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-geocoder/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-geocoder/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-geocoder/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-geocoder/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-geocoder/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-geocoder/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-geocoder/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-geocoder/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-geocoder/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-geocoder/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-geocoder/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-geocoder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-geocoder/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-geocoder/build/test-report.html](https://npmtest.github.io/node-npmtest-node-geocoder/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-geocoder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-geocoder/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-geocoder/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-geocoder/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-geocoder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-geocoder/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-geocoder/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-geocoder/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "nchaulet"
    },
    "bugs": {
        "url": "https://github.com/nchaulet/node-geocoder/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.6",
        "request": "^2.74.0",
        "request-promise": "^4.1.1"
    },
    "description": "Node Geocoder, node geocoding library, supports google maps, mapquest, open street map, tom tom, promise",
    "devDependencies": {
        "chai": "^3.5.0",
        "eslint": "^3.11.0",
        "mocha": "^3.2.0",
        "sinon": "^1.17.3"
    },
    "directories": {},
    "dist": {
        "shasum": "6aa520c06f46fdf723838c0172b61eb646ea7921",
        "tarball": "https://registry.npmjs.org/node-geocoder/-/node-geocoder-3.16.0.tgz"
    },
    "eslintConfig": {
        "env": {
            "node": true
        },
        "rules": {
            "strict": 0,
            "quotes": [
                1,
                "single"
            ],
            "no-console": 1,
            "camelcase": 0,
            "no-underscore-dangle": 0,
            "no-shadow": 0,
            "no-multi-spaces": 0,
            "eqeqeq": 0,
            "key-spacing": 0,
            "comma-spacing": 0,
            "no-unreachable": 1
        }
    },
    "gitHead": "0a1ab93af3bc5eaa215fee82946daa255af0c0f3",
    "homepage": "https://github.com/nchaulet/node-geocoder#readme",
    "keywords": [
        "geocoder",
        "geocoding",
        "geo",
        "google",
        "maps",
        "mapquest",
        "agol",
        "arcgis",
        "tomtom"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "nchaulet"
        }
    ],
    "name": "node-geocoder",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nchaulet/node-geocoder.git"
    },
    "scripts": {
        "ci": "npm run lint && npm run test",
        "lint": "eslint lib",
        "test": "mocha --check-leaks"
    },
    "version": "3.16.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
