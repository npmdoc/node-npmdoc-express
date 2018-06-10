# npmdoc-express

#### basic api documentation for  [express (4.16.3)](http://expressjs.com/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express)

#### Fast, unopinionated, minimalist web framework

[![NPM](https://nodei.co/npm/express.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express)

- [https://npmdoc.github.io/node-npmdoc-express/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bugs": {
        "url": "https://github.com/expressjs/express/issues"
    },
    "contributors": [
        {
            "name": "Aaron Heckmann"
        },
        {
            "name": "Ciaran Jessup"
        },
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Guillermo Rauch"
        },
        {
            "name": "Jonathan Ong"
        },
        {
            "name": "Roman Shtylman"
        },
        {
            "name": "Young Jae Sim"
        }
    ],
    "dependencies": {
        "accepts": "~1.3.5",
        "array-flatten": "1.1.1",
        "body-parser": "1.18.2",
        "content-disposition": "0.5.2",
        "content-type": "~1.0.4",
        "cookie": "0.3.1",
        "cookie-signature": "1.0.6",
        "debug": "2.6.9",
        "depd": "~1.1.2",
        "encodeurl": "~1.0.2",
        "escape-html": "~1.0.3",
        "etag": "~1.8.1",
        "finalhandler": "1.1.1",
        "fresh": "0.5.2",
        "merge-descriptors": "1.0.1",
        "methods": "~1.1.2",
        "on-finished": "~2.3.0",
        "parseurl": "~1.3.2",
        "path-to-regexp": "0.1.7",
        "proxy-addr": "~2.0.3",
        "qs": "6.5.1",
        "range-parser": "~1.2.0",
        "safe-buffer": "5.1.1",
        "send": "0.16.2",
        "serve-static": "1.13.2",
        "setprototypeof": "1.1.0",
        "statuses": "~1.4.0",
        "type-is": "~1.6.16",
        "utils-merge": "1.0.1",
        "vary": "~1.1.2"
    },
    "description": "Fast, unopinionated, minimalist web framework",
    "devDependencies": {
        "after": "0.8.2",
        "connect-redis": "~2.4.1",
        "cookie-parser": "~1.4.3",
        "cookie-session": "1.3.2",
        "ejs": "2.5.7",
        "eslint": "2.13.1",
        "express-session": "1.15.6",
        "hbs": "4.0.1",
        "istanbul": "0.4.5",
        "marked": "0.3.17",
        "method-override": "2.3.10",
        "mocha": "3.5.3",
        "morgan": "1.9.0",
        "multiparty": "4.1.3",
        "pbkdf2-password": "1.2.1",
        "should": "13.2.1",
        "supertest": "1.2.0",
        "vhost": "~3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "6af8a502350db3246ecc4becf6b5a34d22f7ed53",
        "tarball": "https://registry.npmjs.org/express/-/express-4.16.3.tgz",
        "fileCount": 16,
        "unpackedSize": 205577
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "LICENSE",
        "History.md",
        "Readme.md",
        "index.js",
        "lib/"
    ],
    "gitHead": "3ed5090ca91f6a387e66370d57ead94d886275e1",
    "homepage": "http://expressjs.com/",
    "keywords": [
        "express",
        "framework",
        "sinatra",
        "web",
        "rest",
        "restful",
        "router",
        "app",
        "api"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "hacksparrow"
        },
        {
            "name": "jasnell"
        },
        {
            "name": "mikeal"
        }
    ],
    "name": "express",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/express.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --require test/support/env --reporter spec --bail --check-leaks --no-exit test/ test/acceptance/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --require test/support/env --reporter spec --check-leaks --no-exit test/ test/acceptance/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require test/support/env --reporter dot --check-leaks --no-exit test/ test/acceptance/",
        "test-tap": "mocha --require test/support/env --reporter tap --check-leaks --no-exit test/ test/acceptance/"
    },
    "version": "4.16.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
