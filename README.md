# npmtest-hyperline

#### basic test coverage for  hyperline (v0.6.1)  [![npm package](https://img.shields.io/npm/v/npmtest-hyperline.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hyperline) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hyperline.svg)](https://travis-ci.org/npmtest/node-npmtest-hyperline)

#### Handy status line for Hyper.app

[![NPM](https://nodei.co/npm/hyperline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hyperline)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hyperline/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperline/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hyperline/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hyperline/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hyperline/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hyperline/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hyperline/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hyperline/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hyperline/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hyperline/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hyperline/build/test-report.html](https://npmtest.github.io/node-npmtest-hyperline/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hyperline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hyperline/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hyperline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hyperline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hyperline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hyperline/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hyperline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hyperline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "hyperline",
    "version": "0.6.1",
    "description": "Handy status line for Hyper.app",
    "keywords": [
        "hyper.app",
        "hyper",
        "hyperterm"
    ],
    "main": "dist/hyperline.js",
    "author": "Nick Tikhonov",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/NickTikhonov/hyperterm-hyperline.git"
    },
    "devDependencies": {
        "babel-core": "^6.11.4",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.11.1",
        "eslint": "^3.3.0",
        "eslint-config-idiomatic": "^2.1.0",
        "eslint-loader": "^1.5.0",
        "eslint-plugin-react": "^6.1.1",
        "webpack": "^1.13.1",
        "webpack-node-externals": "^1.3.3"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "scripts": {
        "build": "NODE_ENV=production webpack",
        "dev": "webpack --watch"
    },
    "dependencies": {
        "color": "^0.11.3",
        "json-loader": "^0.5.4",
        "systeminformation": "^3.4.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
