# test coverage for  [npm-install-webpack-plugin (v4.0.4)](https://github.com/ericclemmons/npm-install-webpack-plugin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-install-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-install-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-install-webpack-plugin.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-install-webpack-plugin)
#### Webpack loader to automatically npm install & save dependencies.

[![NPM](https://nodei.co/npm/npm-install-webpack-plugin.png?downloads=true)](https://www.npmjs.com/package/npm-install-webpack-plugin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-install-webpack-plugin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-install-webpack-plugin/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-npm-install-webpack-plugin%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-install-webpack-plugin/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-npm-install-webpack-plugin%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-install-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-install-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Clemmons",
        "email": "eric@smarterspam.com"
    },
    "bugs": {
        "url": "https://github.com/ericclemmons/npm-install-webpack-plugin/issues"
    },
    "dependencies": {
        "cross-spawn": "^4.0.0",
        "memory-fs": "^0.3.0"
    },
    "description": "Webpack loader to automatically npm install & save dependencies.",
    "devDependencies": {
        "coveralls": "^2.11.8",
        "cross-env": "^1.0.8",
        "expect": "^1.14.0",
        "mocha": "^2.4.5",
        "nyc": "^6.0.0",
        "webpack": "^1.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8097ba6383acc48c11f21e64d85555e894d339dd",
        "tarball": "https://registry.npmjs.org/npm-install-webpack-plugin/-/npm-install-webpack-plugin-4.0.4.tgz"
    },
    "engines": {
        "node": ">=4.2.0"
    },
    "files": [
        "src"
    ],
    "gitHead": "de9c141063de451a4876f4eb75e1bb5680e9153f",
    "homepage": "https://github.com/ericclemmons/npm-install-webpack-plugin#readme",
    "keywords": [
        "webpack",
        "webpack-plugin",
        "npm",
        "install"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "ericclemmons",
            "email": "eric@smarterspam.com"
        }
    ],
    "name": "npm-install-webpack-plugin",
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": "^1.12.0 || ^2.1.0-beta.0 || ^2.1.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ericclemmons/npm-install-webpack-plugin.git"
    },
    "scripts": {
        "changelog": "npm run changelog:generate && npm run changelog:add",
        "changelog:add": "git add CHANGELOG.md",
        "changelog:generate": "github_changelog_generator --future-release $npm_package_version",
        "coverage": "npm test && nyc report --reporter=text-lcov | coveralls",
        "postversion": "npm run version:amend && git push origin master --tags && npm publish",
        "test": "cross-env NODE_ENV=test nyc mocha",
        "version": "npm run changelog",
        "version:amend": "git commit --amend -m \"Release v${npm_package_version}\""
    },
    "version": "4.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
