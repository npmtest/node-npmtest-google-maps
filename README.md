# npmtest-google-maps

#### basic test coverage for  google-maps (v3.2.1)  [![npm package](https://img.shields.io/npm/v/npmtest-google-maps.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-maps) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-maps.svg)](https://travis-ci.org/npmtest/node-npmtest-google-maps)

#### Wrapper for asynchronously used Google Maps API

[![NPM](https://nodei.co/npm/google-maps.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-maps)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-maps/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-maps/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-maps/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-maps/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-maps/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-maps/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-maps/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-google-maps/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-google-maps/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-maps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-google-maps/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-google-maps/build/test-report.html](https://npmtest.github.io/node-npmtest-google-maps/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-maps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-maps/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-google-maps/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-maps/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-maps/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-maps/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-google-maps/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-google-maps/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "google-maps",
    "description": "Wrapper for asynchronously used Google Maps API",
    "version": "3.2.1",
    "author": {
        "name": "David Kudera"
    },
    "keywords": [
        "google",
        "maps",
        "asynchronous",
        "browser",
        "wrapper"
    ],
    "repository": {
        "type": "git",
        "url": "git@github.com:Carrooi/Js-GoogleMapsLoader.git"
    },
    "license": "MIT",
    "engines": {
        "node": "*"
    },
    "main": "./lib/Google.js",
    "devDependencies": {
        "uglify-js": "~2.4.0",
        "mocha": "~2.2.0",
        "mocha-phantomjs": "~3.5.0",
        "phantomjs": "~1.9.0",
        "chai": "~2.3.0"
    },
    "scripts": {
        "minify": "node ./node_modules/uglify-js/bin/uglifyjs ./lib/Google.js -o ./lib/Google.min.js",
        "test": "node ./node_modules/mocha-phantomjs/bin/mocha-phantomjs -p ./node_modules/phantomjs/bin/phantomjs ./test/index.html"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
