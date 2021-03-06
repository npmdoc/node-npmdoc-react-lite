# npmdoc-react-lite

#### basic api documentation for  [react-lite (v0.15.34)](https://github.com/Lucifier129/react-lite)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-lite.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-lite) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-lite.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-lite)

#### an implementation of React that optimizes for small script size

[![NPM](https://nodei.co/npm/react-lite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-lite)

- [https://npmdoc.github.io/node-npmdoc-react-lite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-lite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-lite/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-lite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-lite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jade Gu",
        "url": "https://github.com/Lucifier129"
    },
    "bugs": {
        "url": "https://github.com/Lucifier129/react-lite/issues"
    },
    "dependencies": {},
    "description": "an implementation of React that optimizes for small script size",
    "devDependencies": {
        "babel": "^5.8.35",
        "babel-core": "^5.8.25",
        "babel-jest": "^5.3.0",
        "babel-loader": "^5.3.2",
        "babel-runtime": "^5.8.25",
        "jest-cli": "^0.8.1",
        "jest-webpack-alias": "^2.0.0",
        "rollup": "^0.21.0",
        "rollup-plugin-babel": "^1.0.0",
        "rollup-plugin-replace": "^1.1.0",
        "uglify-js": "^2.6.1",
        "webpack": "^1.12.2"
    },
    "directories": {},
    "dist": {
        "shasum": "650604d700c8209f37f46195bb21d5c73c018aa1",
        "tarball": "https://registry.npmjs.org/react-lite/-/react-lite-0.15.34.tgz"
    },
    "gitHead": "88815d8579c4a6175135028273037557a0675f8d",
    "homepage": "https://github.com/Lucifier129/react-lite",
    "jest": {
        "scriptPreprocessor": "<rootDir>/jest/preprocessor.js",
        "persistModuleRegistryBetweenSpecs": true,
        "unmockedModulePathPatterns": [
            ""
        ]
    },
    "jsnext:main": "src/index.js",
    "keywords": [
        "react",
        "lite",
        "react-lite",
        "component",
        "virtual-dom"
    ],
    "license": "MIT",
    "main": "dist/react-lite.common.js",
    "maintainers": [
        {
            "name": "lucifier129"
        }
    ],
    "name": "react-lite",
    "npmFileMap": [
        {
            "basePath": "/dist/",
            "files": [
                "*.js"
            ]
        }
    ],
    "npmName": "react-lite",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Lucifier129/react-lite.git"
    },
    "scripts": {
        "build": "node build.js && npm run build:addons",
        "build:addons": "babel ./addons --out-dir ./lib",
        "prepublish": "npm test && npm run build",
        "test": "jest"
    },
    "version": "0.15.34",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
