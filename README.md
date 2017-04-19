# npmdoc-rnpm

#### api documentation for  [rnpm (v1.9.0)](https://github.com/rnpm/rnpm#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-rnpm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rnpm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rnpm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rnpm)

#### React Native Package Manager

[![NPM](https://nodei.co/npm/rnpm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rnpm)

- [https://npmdoc.github.io/node-npmdoc-rnpm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rnpm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rnpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rnpm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rnpm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rnpm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Amazing React Native Community",
        "url": "https://github.com/facebook/react-native"
    },
    "bin": {
        "rnpm": "bin/cli"
    },
    "bugs": {
        "url": "https://github.com/rnpm/rnpm/issues"
    },
    "contributors": [
        {
            "name": "Alexey Kureev",
            "url": "https://github.com/Kureev"
        },
        {
            "name": "Mike Grabowski",
            "url": "https://github.com/grabbou"
        }
    ],
    "dependencies": {
        "commander": "^2.9.0",
        "glob": "^7.0.1",
        "lodash": "^3.10.1",
        "rnpm-plugin-install": "^1.1.0",
        "rnpm-plugin-link": "^1.8.0",
        "update-notifier": "^0.6.0",
        "xmldoc": "^0.4.0"
    },
    "description": "React Native Package Manager",
    "devDependencies": {
        "babel-eslint": "^4.1.5",
        "eslint": "^1.9.0",
        "jest-cli": "^0.9.0-fb2",
        "mock-fs": "^3.9.0",
        "mock-require": "^1.2.1",
        "rewire": "^2.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0a6670fb3facc2cddb7df38a07e5b495e423e79c",
        "tarball": "https://registry.npmjs.org/rnpm/-/rnpm-1.9.0.tgz"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "7acee5113d0d4ca52d0c4f16422faf2960447a34",
    "homepage": "https://github.com/rnpm/rnpm#readme",
    "jest": {
        "testDirectoryName": "test",
        "collectCoverage": true,
        "testRunner": "<rootDir>/node_modules/jest-cli/src/testRunners/jasmine/jasmine2.js"
    },
    "keywords": [
        "react-native",
        "native-modules",
        "packager",
        "rnpm"
    ],
    "license": "MIT",
    "main": "./src/getCommands.js",
    "maintainers": [
        {
            "name": "grabbou"
        },
        {
            "name": "kureev"
        }
    ],
    "name": "rnpm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rnpm/rnpm.git"
    },
    "scripts": {
        "test": "jest"
    },
    "version": "1.9.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
