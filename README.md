# npmtest-svg-sprite-generator

#### basic test coverage for  [svg-sprite-generator (v0.0.7)](https://github.com/frexy/svg-sprite-generator)  [![npm package](https://img.shields.io/npm/v/npmtest-svg-sprite-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg-sprite-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg-sprite-generator.svg)](https://travis-ci.org/npmtest/node-npmtest-svg-sprite-generator)

#### A SVG sprite file generator

[![NPM](https://nodei.co/npm/svg-sprite-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg-sprite-generator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg-sprite-generator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg-sprite-generator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg-sprite-generator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/test-report.html](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg-sprite-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg-sprite-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg-sprite-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg-sprite-generator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg-sprite-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "svg-sprite-generator",
    "version": "0.0.7",
    "description": "A SVG sprite file generator",
    "main": "./lib/main.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/frexy/svg-sprite-generator.git"
    },
    "bin": {
        "svg-sprite-generate": "bin/svg-sprite-generate"
    },
    "keywords": [
        "svg",
        "sprite",
        "generator"
    ],
    "author": "Huy Nguyen",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/frexy/svg-sprite-generator/issues"
    },
    "homepage": "https://github.com/frexy/svg-sprite-generator",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-exec": "^0.4.6"
    },
    "dependencies": {
        "async": "^1.3.0",
        "cheerio": "^0.19.0",
        "commander": "^2.8.1",
        "es6-promise": "^2.3.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
