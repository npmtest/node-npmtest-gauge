# npmtest-gauge

#### basic test coverage for  [gauge (v2.7.4)](https://github.com/iarna/gauge)  [![npm package](https://img.shields.io/npm/v/npmtest-gauge.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gauge) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gauge.svg)](https://travis-ci.org/npmtest/node-npmtest-gauge)

#### A terminal based horizontal guage

[![NPM](https://nodei.co/npm/gauge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gauge)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gauge/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gauge/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gauge/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gauge/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gauge/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gauge/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gauge/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gauge/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gauge/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gauge/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gauge/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gauge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gauge/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gauge/build/test-report.html](https://npmtest.github.io/node-npmtest-gauge/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gauge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gauge/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gauge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gauge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gauge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gauge/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gauge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gauge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rebecca Turner"
    },
    "bugs": {
        "url": "https://github.com/iarna/gauge/issues"
    },
    "dependencies": {
        "aproba": "^1.0.3",
        "console-control-strings": "^1.0.0",
        "has-unicode": "^2.0.0",
        "object-assign": "^4.1.0",
        "signal-exit": "^3.0.0",
        "string-width": "^1.0.1",
        "strip-ansi": "^3.0.1",
        "wide-align": "^1.1.0"
    },
    "description": "A terminal based horizontal guage",
    "devDependencies": {
        "readable-stream": "^2.0.6",
        "require-inject": "^1.4.0",
        "standard": "^7.1.2",
        "tap": "^5.7.2",
        "through2": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2c03405c7538c39d7eb37b317022e325fb018bf7",
        "tarball": "https://registry.npmjs.org/gauge/-/gauge-2.7.4.tgz"
    },
    "files": [
        "base-theme.js",
        "CHANGELOG.md",
        "error.js",
        "has-color.js",
        "index.js",
        "LICENSE",
        "package.json",
        "plumbing.js",
        "process.js",
        "progress-bar.js",
        "README.md",
        "render-template.js",
        "set-immediate.js",
        "set-interval.js",
        "spin.js",
        "template-item.js",
        "theme-set.js",
        "themes.js",
        "wide-truncate.js"
    ],
    "gitHead": "1011abf6c2cb7ae89a3ee76fb447d3182d4e8d3a",
    "homepage": "https://github.com/iarna/gauge",
    "keywords": [
        "progressbar",
        "progress",
        "gauge"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "iarna"
        }
    ],
    "name": "gauge",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/iarna/gauge.git"
    },
    "scripts": {
        "prepublish": "rm -f *~",
        "test": "standard && tap test/*.js --coverage"
    },
    "version": "2.7.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
