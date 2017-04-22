# npmtest-brunch

#### basic test coverage for  [brunch (v2.10.9)](http://brunch.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-brunch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-brunch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-brunch.svg)](https://travis-ci.org/npmtest/node-npmtest-brunch)

#### Fast front-end web app build tool with simple declarative config, seamless incremental compilation for rapid development, an opinionated pipeline and workflow, and core support for source maps

[![NPM](https://nodei.co/npm/brunch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/brunch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-brunch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-brunch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-brunch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-brunch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-brunch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-brunch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-brunch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-brunch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-brunch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-brunch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-brunch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-brunch/build/test-report.html](https://npmtest.github.io/node-npmtest-brunch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-brunch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-brunch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-brunch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-brunch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-brunch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-brunch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-brunch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-brunch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brunch team",
        "url": "http://brunch.io"
    },
    "bin": {
        "brunch": "./bin/brunch"
    },
    "bugs": {
        "url": "https://github.com/brunch/brunch/issues"
    },
    "dependencies": {
        "anymatch": "~1.3",
        "anysort": "~1.0",
        "check-dependencies": "~1.0.1",
        "chokidar": "^1.6",
        "coffee-script": "~1.11",
        "commander": "~2.9",
        "commonjs-require-definition": "~0.6.2",
        "debug": "~2.2",
        "deppack": "~0.7",
        "deps-install": "~0.1",
        "fcache": "~0.3",
        "init-skeleton": "~1.0",
        "loggy": "~1.0.2",
        "micro-es7-shim": "^0.1",
        "micro-promisify": "~0.1",
        "mkdirp": "~0.5",
        "promise.prototype.finally": "^2",
        "read-components": "~0.7",
        "serve-brunch": "~0.2",
        "since-app-start": "~0.3",
        "skemata": "~0.1",
        "source-map": "~0.5",
        "universal-path": "^0.1"
    },
    "description": "Fast front-end web app build tool with simple declarative config, seamless incremental compilation for rapid development, an opinionated pipeline and workflow, and core support for source maps",
    "devDependencies": {
        "ava": "~0.16",
        "eslint": "^3",
        "eslint-config-brunch": "^1",
        "fixturify": "^0.2",
        "fs-extra": "^0.30",
        "nyc": "^6.4.2",
        "rewire": "^2.5",
        "test-console": "^1"
    },
    "directories": {},
    "dist": {
        "shasum": "a74bb5aef87fa87ce0dd4ca4f996610204358d30",
        "tarball": "https://registry.npmjs.org/brunch/-/brunch-2.10.9.tgz"
    },
    "engines": {
        "node": ">= 4.0",
        "npm": ">= 3.0"
    },
    "eslintConfig": {
        "extends": "brunch"
    },
    "files": [
        "bin",
        "lib"
    ],
    "gitHead": "9184f2d6c6487a99c9819bc3b4e5ce1051c76038",
    "homepage": "http://brunch.io/",
    "keywords": [
        "assembler",
        "builder",
        "stack",
        "pipeline",
        "build tool",
        "workflow",
        "source map",
        "incremental",
        "config",
        "react",
        "webpack",
        "browserify",
        "grunt",
        "gulp",
        "broccoli",
        "backbone",
        "ember",
        "angular",
        "chaplin",
        "html5"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "tosh"
        },
        {
            "name": "nikgraf"
        },
        {
            "name": "paulmillr"
        },
        {
            "name": "es128"
        }
    ],
    "name": "brunch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/brunch/brunch.git"
    },
    "scripts": {
        "lint": "eslint bin/brunch lib test",
        "lint:fix": "eslint --fix bin/brunch lib test",
        "test": "npm run lint && LOGGY_STACKS=1 ava -s --verbose --fail-fast",
        "test:coverage": "nyc ava -s && nyc report --reporter=html"
    },
    "version": "2.10.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
