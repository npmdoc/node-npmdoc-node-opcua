# npmdoc-node-opcua

#### api documentation for  [node-opcua (v0.0.64)](http://node-opcua.github.io/)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-opcua.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-opcua) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-opcua.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-opcua)

#### pure nodejs OPCUA SDK

[![NPM](https://nodei.co/npm/node-opcua.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-opcua)

- [https://npmdoc.github.io/node-npmdoc-node-opcua/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-opcua/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-opcua/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-opcua/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-opcua/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-opcua/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-opcua",
    "version": "0.0.64",
    "description": "pure nodejs OPCUA SDK",
    "homepage": "http://node-opcua.github.io/",
    "main": "index.js",
    "bin": {},
    "directories": {
        "test": "test"
    },
    "scripts": {
        "_x_preinstall": "npm i browserify -g",
        "postinstall": "node postinstall.js",
        "pretest": "node bin/crypto_create_CA.js demo --dev --silent",
        "test": "mocha test --color -R spec --recursive --timeout 200000 --bail",
        "generate_doc": "make doc",
        "generate_autodoc": "./node_modules/autodoc/bin/autodoc -o _tmp_generated_doc bin/binaryStream.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/node-opcua/node-opcua.git"
    },
    "keywords": [
        "OPCUA",
        "opcua",
        "m2m",
        "iot",
        "opc ua",
        "internet of things"
    ],
    "author": "Etienne Rossignon",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/node-opcua/node-opcua/issues"
    },
    "devDependencies": {
        "app-module-path": "^2.2.0",
        "autodoc": "0.6.4",
        "benchmark": "2.1.4",
        "bignumber.js": "4.0.1",
        "coveralls": "2.13.0",
        "csv": "1.1.1",
        "cucumber": "^2.0.0-rc.7",
        "enum": "2.4.0",
        "eyes": "0.1.8",
        "jsdoc": "3.4.3",
        "litpro": "2.0.0",
        "mocha": "3.2.0",
        "mocha-lcov-reporter": "1.3.0",
        "request": "2.81.0",
        "should": "11.2.1",
        "sinon": "2.1.0",
        "tmp": "0.0.31",
        "tracer": "0.8.7",
        "yuidoc-bootstrap-theme": "*",
        "yuidocjs": "*"
    },
    "typings": "./node-opcua.d.ts",
    "dependencies": {
        "async": "2.3.0",
        "backoff": "2.5.0",
        "better-assert": "1.0.2",
        "bomstrip": "0.1.4",
        "byline": "5.0.0",
        "colors": "1.1.2",
        "date-utils": "^1.2.21",
        "deassertify": "^0.1.2",
        "delayed": "^1.0.1",
        "dequeue": "^1.0.5",
        "easy-table": "^1.1.0",
        "exit": "^0.1.2",
        "fqdn": "0.0.3",
        "hexy": "0.2.9",
        "humanize": "0.0.9",
        "ltx": "^2.7.1",
        "moment": "^2.18.1",
        "node-jsrsasign": "0.0.7",
        "node-opcua-crypto": "0.0.8",
        "node-opcua-pki": "0.0.12",
        "once": "^1.4.0",
        "progress": "2.0.0",
        "q": "^1.5.0",
        "requirish": "0.3.0",
        "set-prototype-of": "^1.0.0",
        "sprintf": "0.1.5",
        "timespan": "^2.3.0",
        "treeify": "1.0.1",
        "underscore": "1.8.3",
        "wget-improved": "^1.4.0",
        "xml-writer": "^1.7.0",
        "yargs": "^7.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
