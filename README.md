# npmtest-native-dns

#### basic test coverage for  [native-dns (v0.7.0)](http://github.com/tjfontaine/node-dns)  [![npm package](https://img.shields.io/npm/v/npmtest-native-dns.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-native-dns) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-native-dns.svg)](https://travis-ci.org/npmtest/node-npmtest-native-dns)

#### Replacement for the core DNS module, includes server implementation

[![NPM](https://nodei.co/npm/native-dns.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/native-dns)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-native-dns/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-native-dns/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-native-dns/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-native-dns/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-native-dns/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-native-dns/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-native-dns/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-native-dns/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-native-dns/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-native-dns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-native-dns/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-native-dns/build/test-report.html](https://npmtest.github.io/node-npmtest-native-dns/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-native-dns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-native-dns/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-native-dns/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-native-dns/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-native-dns/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-native-dns/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-native-dns/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-native-dns/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Timothy J Fontaine <tjfontaine@gmail.com> (http://atxconsulting.com)",
        "Greg Slepak <contact@taoeffect.com> (https://twitter.com/taoeffect)",
        "Matthieu Rakotojaona"
    ],
    "bugs": {
        "url": "http://github.com/tjfontaine/node-dns/issues"
    },
    "contributors": [
        {
            "name": "Timothy J Fontaine"
        }
    ],
    "dependencies": {
        "ipaddr.js": "~0.1.3",
        "native-dns-cache": "~0.0.2",
        "native-dns-packet": "~0.1.1"
    },
    "description": "Replacement for the core DNS module, includes server implementation",
    "devDependencies": {
        "nodeunit": ">= 0.7.4",
        "optimist": ""
    },
    "directories": {},
    "dist": {
        "shasum": "df418636f08fb29e8fcb7ef142c822a1588ba5b7",
        "tarball": "https://registry.npmjs.org/native-dns/-/native-dns-0.7.0.tgz"
    },
    "engines": {
        "node": ">= 0.5.0"
    },
    "gitHead": "6ce835d9625a45ea7c8e8e71e36e1ebee767969e",
    "homepage": "http://github.com/tjfontaine/node-dns",
    "keywords": [
        "dns",
        "bind",
        "native"
    ],
    "main": "dns.js",
    "maintainers": [
        {
            "name": "tjfontaine"
        },
        {
            "name": "taoeffect"
        }
    ],
    "name": "native-dns",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/tjfontaine/node-dns.git"
    },
    "scripts": {
        "test": "nodeunit test"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
