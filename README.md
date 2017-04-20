# npmtest-esperanto

#### basic test coverage for  esperanto (v0.7.6)  [![npm package](https://img.shields.io/npm/v/npmtest-esperanto.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-esperanto) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-esperanto.svg)](https://travis-ci.org/npmtest/node-npmtest-esperanto)

#### An easier way to convert ES6 modules to AMD and CommonJS

[![NPM](https://nodei.co/npm/esperanto.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/esperanto)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-esperanto/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-esperanto/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-esperanto/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-esperanto/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-esperanto/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-esperanto/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-esperanto/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-esperanto/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-esperanto/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-esperanto/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-esperanto/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-esperanto/build/test-report.html](https://npmtest.github.io/node-npmtest-esperanto/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-esperanto/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-esperanto/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-esperanto/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-esperanto/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-esperanto/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-esperanto/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-esperanto/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-esperanto/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "esperanto",
    "description": "An easier way to convert ES6 modules to AMD and CommonJS",
    "version": "0.7.6",
    "author": "Rich Harris",
    "repository": "https://github.com/esperantojs/esperanto",
    "license": "MIT",
    "dependencies": {
        "acorn": "^1.0.1",
        "chalk": "^1.0.0",
        "magic-string": "^0.4.9",
        "minimist": "^1.1.0",
        "sander": "^0.5.1"
    },
    "main": "dist/esperanto.js",
    "jsnext:main": "src/esperanto.js",
    "bin": {
        "esperanto": "./bin/index.js"
    },
    "devDependencies": {
        "gobble": "^0.7.2",
        "gobble-babel": "^5.1.0",
        "gobble-cli": "^0.4.2",
        "gobble-esperanto-bundle": "^0.2.0",
        "gobble-uglifyjs": "^0.1.0",
        "magic-string": "^0.6.0",
        "mocha": "^2.1.0",
        "resolve": "^1.1.0",
        "source-map": "^0.1.40",
        "source-map-support": "^0.2.10"
    },
    "files": [
        "esperanto.js",
        "src",
        "dist",
        "bin",
        "README.md"
    ],
    "scripts": {
        "build": "gobble build -f dist",
        "pretest": "npm run build",
        "test": "mocha",
        "prepublish": "npm test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
