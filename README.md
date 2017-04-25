# npmtest-headroom.js

#### basic test coverage for  [headroom.js (v0.9.3)](http://wicky.nillia.ms/headroom.js)  [![npm package](https://img.shields.io/npm/v/npmtest-headroom.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-headroom.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-headroom.js.svg)](https://travis-ci.org/npmtest/node-npmtest-headroom.js)

#### Give your page some headroom. Hide your header until you need it

[![NPM](https://nodei.co/npm/headroom.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/headroom.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-headroom.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-headroom.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-headroom.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-headroom.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-headroom.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-headroom.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-headroom.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-headroom.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-headroom.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-headroom.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-headroom.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-headroom.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-headroom.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-headroom.js/build/test-report.html](https://npmtest.github.io/node-npmtest-headroom.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-headroom.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-headroom.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-headroom.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-headroom.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-headroom.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-headroom.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-headroom.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-headroom.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Williams"
    },
    "bugs": {
        "url": "https://github.com/WickyNilliams/headroom.js/issues"
    },
    "dependencies": {},
    "description": "Give your page some headroom. Hide your header until you need it",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^0.11.1",
        "grunt-contrib-watch": "~0.5.1",
        "grunt-karma": "~0.6.2",
        "grunt-rigger": "~0.5.0",
        "karma": "~0.10.8",
        "karma-firefox-launcher": "~0.1.2",
        "karma-opera-launcher": "~0.1.0",
        "karma-safari-launcher": "~0.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6d48499a2b9883fcc0683b26f461e732f149a1fe",
        "tarball": "https://registry.npmjs.org/headroom.js/-/headroom.js-0.9.3.tgz"
    },
    "files": [
        "dist",
        "bower.json"
    ],
    "gitHead": "66d495814c56ab581679363a783fa0d2fc4da32e",
    "homepage": "http://wicky.nillia.ms/headroom.js",
    "keywords": [
        "header",
        "fixed",
        "scroll",
        "menu"
    ],
    "license": "MIT",
    "main": "dist/headroom.js",
    "maintainers": [
        {
            "name": "iduuck"
        },
        {
            "name": "wickynilliams"
        }
    ],
    "name": "headroom.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/WickyNilliams/headroom.js.git"
    },
    "scripts": {
        "build": "grunt dist",
        "postversion": "git push origin master --tags && npm publish",
        "start": "grunt",
        "test": "grunt test --verbose",
        "version": "npm run build"
    },
    "version": "0.9.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
