# npmtest-inversify

#### basic test coverage for  [inversify (v3.3.0)](http://inversify.io)  [![npm package](https://img.shields.io/npm/v/npmtest-inversify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-inversify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-inversify.svg)](https://travis-ci.org/npmtest/node-npmtest-inversify)

#### A powerful and lightweight inversion of control container for JavaScript and Node.js apps powered by TypeScript.

[![NPM](https://nodei.co/npm/inversify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/inversify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-inversify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-inversify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-inversify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-inversify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-inversify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-inversify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-inversify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-inversify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-inversify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-inversify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-inversify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-inversify/build/test-report.html](https://npmtest.github.io/node-npmtest-inversify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-inversify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-inversify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-inversify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-inversify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inversify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inversify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-inversify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-inversify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Remo H. Jansen"
    },
    "bugs": {
        "url": "https://github.com/inversify/InversifyJS/issues"
    },
    "dependencies": {},
    "description": "A powerful and lightweight inversion of control container for JavaScript and Node.js apps powered by TypeScript.",
    "devDependencies": {
        "@types/chai": "^3.4.32",
        "@types/harmony-proxy": "^1.0.27",
        "@types/mocha": "^ 2.2.35",
        "@types/sinon": "^1.16.29",
        "bluebird": "^3.5.0",
        "browserify": "^14.0.0",
        "chai": "^3.4.1",
        "del": "^2.2.2",
        "es6-symbol": "^3.1.0",
        "gulp": "^3.9.0",
        "gulp-istanbul": "^1.0.0",
        "gulp-mocha": "^4.0.0",
        "gulp-rename": "^1.2.2",
        "gulp-sourcemaps": "^2.2.1",
        "gulp-tslint": "^7.0.0",
        "gulp-typescript": "^3.0.0",
        "gulp-uglify": "^2.0.0",
        "harmonize": "^2.0.0",
        "harmony-proxy": "^1.0.0",
        "istanbul": "^0.4.2",
        "karma": "^1.1.2",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-commonjs": "^1.0.0",
        "karma-es6-shim": "^1.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-ie-launcher": "^1.0.0",
        "karma-mocha": "^1.1.1",
        "karma-mocha-reporter": "^2.0.5",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sinon": "^1.0.5",
        "mocha": "^3.0.1",
        "performance-now": "^2.0.0",
        "publish-please": "^2.1.4",
        "reflect-metadata": "^0.1.9",
        "run-sequence": "^1.2.0",
        "sinon": "^2.0.0",
        "tslint": "^4.4.2",
        "typescript": "^2.2.0",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {
        "test": "gulp"
    },
    "dist": {
        "shasum": "57ca2e0aaac7b54aa5018ad69a10c5aba366e96e",
        "tarball": "https://registry.npmjs.org/inversify/-/inversify-3.3.0.tgz"
    },
    "engines": {},
    "gitHead": "95c8f3aeedaf2511d246487f4fcf823c97a511f6",
    "homepage": "http://inversify.io",
    "jsnext:main": "es/inversify.js",
    "keywords": [
        "ioc",
        "di",
        "javascript",
        "typescript",
        "node",
        "dependency injection",
        "dependency inversion",
        "inversion of control container"
    ],
    "license": "MIT",
    "main": "lib/inversify.js",
    "maintainers": [
        {
            "name": "remojansen"
        }
    ],
    "name": "inversify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/inversify/InversifyJS.git"
    },
    "scripts": {
        "prepublish": "publish-please guard",
        "publish-please": "publish-please",
        "test": "gulp"
    },
    "typings": "./dts/inversify.d.ts",
    "version": "3.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
