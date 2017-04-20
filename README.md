# npmdoc-jstransformer

#### api documentation for  jstransformer (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-jstransformer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jstransformer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jstransformer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jstransformer)

#### Normalize the API of any jstransformer

[![NPM](https://nodei.co/npm/jstransformer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jstransformer)

- [https://npmdoc.github.io/node-npmdoc-jstransformer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jstransformer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jstransformer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jstransformer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jstransformer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jstransformer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jstransformer",
    "version": "1.0.0",
    "description": "Normalize the API of any jstransformer",
    "keywords": [
        "jstransformer"
    ],
    "dependencies": {
        "is-promise": "^2.0.0",
        "promise": "^7.0.1"
    },
    "devDependencies": {
        "coveralls": "^2.11.2",
        "istanbul": "^0.4.0",
        "testit": "^2.0.2"
    },
    "scripts": {
        "test": "node test",
        "coverage": "istanbul cover test",
        "coveralls": "npm run coverage && cat ./coverage/lcov.info | coveralls"
    },
    "files": [
        "index.js"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/jstransformers/jstransformer.git"
    },
    "author": "ForbesLindesay",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
