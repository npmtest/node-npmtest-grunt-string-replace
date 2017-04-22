# npmtest-grunt-string-replace

#### basic test-coverage for  [grunt-string-replace (v1.3.1)](https://github.com/eruizdechavez/grunt-string-replace)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-string-replace.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-string-replace) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-string-replace.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-string-replace)

#### Replaces strings on files by using string or regex patterns. Attempts to be a String.prototype.replace adapter task for your grunt project.

[![NPM](https://nodei.co/npm/grunt-string-replace.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-string-replace)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-string-replace/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-string-replace/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-string-replace/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-string-replace/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-string-replace/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-string-replace/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-string-replace/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-string-replace/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-string-replace/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-string-replace/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erick Ruiz de Chavez",
        "url": "http://erickruizdechavez.com"
    },
    "bin": {
        "grunt-string-replace": "bin/grunt-string-replace"
    },
    "bugs": {
        "url": "https://github.com/eruizdechavez/grunt-string-replace/issues"
    },
    "dependencies": {
        "async": "^2.0.0",
        "chalk": "^1.0.0"
    },
    "description": "Replaces strings on files by using string or regex patterns. Attempts to be a String.prototype.replace adapter task for your grunt project.",
    "devDependencies": {
        "grunt": "^1.0.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-nodeunit": "^1.0.0",
        "grunt-contrib-watch": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "633a03bc78482a0e0e1f9df7f645811fc1fbb162",
        "tarball": "https://registry.npmjs.org/grunt-string-replace/-/grunt-string-replace-1.3.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0",
        "npm": ">= 1.4.15"
    },
    "gitHead": "e82e61da78cde742dd9d3f94138bda5e31984c9f",
    "homepage": "https://github.com/eruizdechavez/grunt-string-replace",
    "keywords": [
        "gruntplugin",
        "string",
        "replace",
        "regex"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/eruizdechavez/grunt-string-replace/blob/master/LICENSE-MIT"
        }
    ],
    "main": "tasks/string-replace",
    "maintainers": [
        {
            "name": "eruizdechavez"
        }
    ],
    "name": "grunt-string-replace",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/eruizdechavez/grunt-string-replace.git"
    },
    "scripts": {
        "postversion": "git push && git push --tags",
        "preversion": "npm test",
        "test": "grunt --verbose --env=test"
    },
    "version": "1.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
