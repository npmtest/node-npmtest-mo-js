# npmtest-mo-js

#### test coverage for  [mo-js (v0.288.1)](https://github.com/legomushroom/mojs)  [![npm package](https://img.shields.io/npm/v/npmtest-mo-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mo-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mo-js.svg)](https://travis-ci.org/npmtest/node-npmtest-mo-js)

#### motion graphics toolbelt for the web

[![NPM](https://nodei.co/npm/mo-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mo-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mo-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mo-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mo-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mo-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mo-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mo-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mo-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mo-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mo-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mo-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mo-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mo-js/build/test-report.html](https://npmtest.github.io/node-npmtest-mo-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mo-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mo-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mo-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mo-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mo-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mo-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mo-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mo-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "LegoMushroom",
        "url": "https://twitter.com/legomushroom"
    },
    "bugs": {
        "url": "https://github.com/legomushroom/mojs/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.5.0"
    },
    "description": "motion graphics toolbelt for the web",
    "devDependencies": {
        "6to5-loader": "^3.0.0",
        "6to5-runtime": "^3.6.5",
        "babel-core": "^6.5.2",
        "babel-loader": "^6.2.2",
        "babel-plugin-transform-es2015-classes": "^6.6.5",
        "babel-plugin-transform-runtime": "^6.5.2",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "babel-preset-stage-2": "^6.11.0",
        "brfs": "^1.2.0",
        "browserify": "^6.2.0",
        "browserify-istanbul": "^0.1.2",
        "browserify-shim": "~3.8.0",
        "chalk": "^0.5.1",
        "coffee-loader": "^0.7.2",
        "coffeeify": "latest",
        "coveralls": "^2.11.2",
        "grock": "git+https://github.com/legomushroom/grock.git",
        "gulp": "latest",
        "gulp-autoprefixer": "0.0.6",
        "gulp-browserify": "latest",
        "gulp-changed": "~0.2.0",
        "gulp-coffee": "~1.4.1",
        "gulp-coffeeify": "^0.1.8",
        "gulp-coffeelint": "*",
        "gulp-concat": "*",
        "gulp-csslint": "*",
        "gulp-insert": "^0.4.0",
        "gulp-jade": "~0.4.2",
        "gulp-json-editor": "^2.2.1",
        "gulp-karma": "*",
        "gulp-livereload": "~1.2.0",
        "gulp-minify-css": "~0.3.0",
        "gulp-notify": "~0.5.1",
        "gulp-plumber": "*",
        "gulp-rename": "latest",
        "gulp-shell": "^0.4.0",
        "gulp-stylus": "latest",
        "gulp-uglify": "latest",
        "gulp-watch": "*",
        "karma": "^0.12.24",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-browserify": "^2.0.0",
        "karma-chrome-launcher": "^0.1.4",
        "karma-clear-screen-reporter": "0.0.1",
        "karma-cli": "0.0.4",
        "karma-coverage": "0.2.6",
        "karma-jasmine": "^0.2.0",
        "karma-phantomjs-launcher": "^0.1.4",
        "karma-sauce-launcher": "^0.2.10",
        "mojs-player": "^0.40.0",
        "nodemon": "*",
        "phantomjs-polyfill": "0.0.2",
        "pygments": "^0.2.0",
        "run-sequence": "^1.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "cd4779b362b6a4a3ddff1c50ce4454c2fd1f7f6d",
        "tarball": "https://registry.npmjs.org/mo-js/-/mo-js-0.288.1.tgz"
    },
    "gitHead": "0b98072e9dfa0c742dfa2db3e2d414f9d1fad1d4",
    "homepage": "https://github.com/legomushroom/mojs",
    "keywords": [
        "motion",
        "effects",
        "animation",
        "motion graphics"
    ],
    "license": "MIT",
    "main": "build/mo.js",
    "maintainers": [
        {
            "name": "legomushroom"
        }
    ],
    "name": "mo-js",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/legomushroom/mojs.git"
    },
    "scripts": {
        "build": "",
        "test": "karma start --single-run"
    },
    "version": "0.288.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
