# npmdoc-mongoose-role

#### api documentation for  [mongoose-role (v2.0.0)](https://github.com/ksmithut/mongoose-role)  [![npm package](https://img.shields.io/npm/v/npmdoc-mongoose-role.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mongoose-role) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mongoose-role.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mongoose-role)

#### Adds a role and access level functionality to a model

[![NPM](https://nodei.co/npm/mongoose-role.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongoose-role)

- [https://npmdoc.github.io/node-npmdoc-mongoose-role/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongoose-role/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongoose-role/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongoose-role/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mongoose-role/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mongoose-role/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mongoose-role",
    "version": "2.0.0",
    "description": "Adds a role and access level functionality to a model",
    "main": "index.js",
    "scripts": {
        "jshint": "jshint --reporter node_modules/jshint-stylish/index.js index.js",
        "check-cov": "istanbul check-coverage --statements 100 --functions 100 --branches 100 --lines 100",
        "test": "istanbul cover _mocha",
        "posttest": " npm run check-cov; npm run jshint;",
        "codeclimate": "cat ./coverage/lcov.info | codeclimate"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/ksmithut/mongoose-role.git"
    },
    "keywords": [
        "mongoose",
        "role",
        "account",
        "acl"
    ],
    "author": "ksmithut",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/ksmithut/mongoose-role/issues"
    },
    "homepage": "https://github.com/ksmithut/mongoose-role",
    "devDependencies": {
        "chai": "^3.5.0",
        "codeclimate-test-reporter": "^0.3.3",
        "expect.js": "^0.3.1",
        "istanbul": "^0.4.5",
        "jshint": "^2.9.3",
        "jshint-stylish": "^2.2.1",
        "mocha": "^3.0.2",
        "mocha-lcov-reporter": "^1.2.0",
        "mongoose": "^4.6.0"
    },
    "dependencies": {
        "object-assign": "^4.1.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
