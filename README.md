# npmtest-lwip

#### basic test coverage for  [lwip (v0.0.9)](https://github.com/EyalAr/lwip)  [![npm package](https://img.shields.io/npm/v/npmtest-lwip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lwip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lwip.svg)](https://travis-ci.org/npmtest/node-npmtest-lwip)

#### Comprehensive, fast, and simple image processing and manipulation

[![NPM](https://nodei.co/npm/lwip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lwip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lwip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lwip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lwip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lwip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lwip/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lwip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lwip/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lwip/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lwip/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lwip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lwip/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lwip/build/test-report.html](https://npmtest.github.io/node-npmtest-lwip/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lwip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lwip/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lwip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lwip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lwip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lwip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lwip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lwip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "lwip",
    "version": "0.0.9",
    "main": "index.js",
    "dependencies": {
        "async": "^2.0.0-rc.5",
        "bindings": "^1.2.1",
        "decree": "0.0.6",
        "nan": "^2.3.2"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "./node_modules/.bin/mocha --opts tests/mocha.opts tests",
        "coverage": "./node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha -- --opts tests/mocha.opts tests",
        "travis": "./node_modules/.bin/istanbul cover --report lcovonly ./node_modules/.bin/_mocha -- --opts tests/mocha.opts --bail tests && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js"
    },
    "gypfile": true,
    "description": "Comprehensive, fast, and simple image processing and manipulation",
    "directories": {
        "example": "examples"
    },
    "devDependencies": {
        "coveralls": "^2.11.9",
        "istanbul": "^0.4.3",
        "mkdirp": "^0.5.1",
        "mocha": "^2.4.5",
        "mocha-lcov-reporter": "^1.2.0",
        "should": "^8.3.2"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/EyalAr/lwip.git"
    },
    "keywords": [
        "image",
        "buffer",
        "manipulate",
        "process",
        "resize",
        "scale",
        "rotate",
        "jpeg",
        "jpg",
        "png",
        "gif",
        "crop",
        "blur",
        "sharpen",
        "batch",
        "flip",
        "mirror",
        "border",
        "padding",
        "hue",
        "saturation",
        "lightness",
        "alpha",
        "transparency",
        "fade",
        "opacity",
        "contain",
        "cover"
    ],
    "author": "Eyal Arubas <eyalarubas@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/EyalAr/lwip/issues"
    },
    "homepage": "https://github.com/EyalAr/lwip",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
