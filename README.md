# api documentation for  [express (v4.15.2)](http://expressjs.com/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express)
#### Fast, unopinionated, minimalist web framework

[![NPM](https://nodei.co/npm/express.png?downloads=true)](https://www.npmjs.com/package/express)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-express_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-express/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bugs": {
        "url": "https://github.com/expressjs/express/issues"
    },
    "contributors": [
        {
            "name": "Aaron Heckmann",
            "email": "aaron.heckmann+github@gmail.com"
        },
        {
            "name": "Ciaran Jessup",
            "email": "ciaranj@gmail.com"
        },
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "Guillermo Rauch",
            "email": "rauchg@gmail.com"
        },
        {
            "name": "Jonathan Ong",
            "email": "me@jongleberry.com"
        },
        {
            "name": "Roman Shtylman",
            "email": "shtylman+expressjs@gmail.com"
        },
        {
            "name": "Young Jae Sim",
            "email": "hanul@hanul.me"
        }
    ],
    "dependencies": {
        "accepts": "~1.3.3",
        "array-flatten": "1.1.1",
        "content-disposition": "0.5.2",
        "content-type": "~1.0.2",
        "cookie": "0.3.1",
        "cookie-signature": "1.0.6",
        "debug": "2.6.1",
        "depd": "~1.1.0",
        "encodeurl": "~1.0.1",
        "escape-html": "~1.0.3",
        "etag": "~1.8.0",
        "finalhandler": "~1.0.0",
        "fresh": "0.5.0",
        "merge-descriptors": "1.0.1",
        "methods": "~1.1.2",
        "on-finished": "~2.3.0",
        "parseurl": "~1.3.1",
        "path-to-regexp": "0.1.7",
        "proxy-addr": "~1.1.3",
        "qs": "6.4.0",
        "range-parser": "~1.2.0",
        "send": "0.15.1",
        "serve-static": "1.12.1",
        "setprototypeof": "1.0.3",
        "statuses": "~1.3.1",
        "type-is": "~1.6.14",
        "utils-merge": "1.0.0",
        "vary": "~1.1.0"
    },
    "description": "Fast, unopinionated, minimalist web framework",
    "devDependencies": {
        "after": "0.8.2",
        "body-parser": "1.17.1",
        "connect-redis": "~2.4.1",
        "cookie-parser": "~1.4.3",
        "cookie-session": "~1.2.0",
        "ejs": "2.5.6",
        "express-session": "1.15.1",
        "istanbul": "0.4.5",
        "jade": "~1.11.0",
        "marked": "0.3.6",
        "method-override": "2.3.7",
        "mocha": "3.2.0",
        "morgan": "1.8.1",
        "multiparty": "4.1.3",
        "pbkdf2-password": "1.2.1",
        "should": "11.2.0",
        "supertest": "1.2.0",
        "vhost": "~3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "af107fc148504457f2dca9a6f2571d7129b97b35",
        "tarball": "https://registry.npmjs.org/express/-/express-4.15.2.tgz"
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
    "gitHead": "d43b074f0b3b56a91f240e62798c932ba104b79a",
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
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "hacksparrow",
            "email": "captain@hacksparrow.com"
        },
        {
            "name": "jasnell",
            "email": "jasnell@gmail.com"
        },
        {
            "name": "mikeal",
            "email": "mikeal.rogers@gmail.com"
        }
    ],
    "name": "express",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/express.git"
    },
    "scripts": {
        "test": "mocha --require test/support/env --reporter spec --bail --check-leaks test/ test/acceptance/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --require test/support/env --reporter spec --check-leaks test/ test/acceptance/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require test/support/env --reporter dot --check-leaks test/ test/acceptance/",
        "test-tap": "mocha --require test/support/env --reporter tap --check-leaks test/ test/acceptance/"
    },
    "version": "4.15.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module express](#apidoc.module.express)
1.  [function <span class="apidocSignatureSpan">express.</span>Route (path)](#apidoc.element.express.Route)
1.  [function <span class="apidocSignatureSpan">express.</span>Router (options)](#apidoc.element.express.Router)
1.  [function <span class="apidocSignatureSpan">express.</span>query (options)](#apidoc.element.express.query)
1.  [function <span class="apidocSignatureSpan">express.</span>static (root, options)](#apidoc.element.express.static)
1.  [function <span class="apidocSignatureSpan">express.</span>view (name, options)](#apidoc.element.express.view)
1.  object <span class="apidocSignatureSpan">express.</span>Route.prototype
1.  object <span class="apidocSignatureSpan">express.</span>application
1.  object <span class="apidocSignatureSpan">express.</span>request
1.  object <span class="apidocSignatureSpan">express.</span>response
1.  object <span class="apidocSignatureSpan">express.</span>utils
1.  object <span class="apidocSignatureSpan">express.</span>view.prototype

#### [module express.Route](#apidoc.module.express.Route)
1.  [function <span class="apidocSignatureSpan">express.</span>Route (path)](#apidoc.element.express.Route.Route)

#### [module express.Route.prototype](#apidoc.module.express.Route.prototype)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>_handles_method (method)](#apidoc.element.express.Route.prototype._handles_method)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>_options ()](#apidoc.element.express.Route.prototype._options)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>acl ()](#apidoc.element.express.Route.prototype.acl)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>all ()](#apidoc.element.express.Route.prototype.all)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>bind ()](#apidoc.element.express.Route.prototype.bind)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>checkout ()](#apidoc.element.express.Route.prototype.checkout)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>connect ()](#apidoc.element.express.Route.prototype.connect)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>copy ()](#apidoc.element.express.Route.prototype.copy)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>delete ()](#apidoc.element.express.Route.prototype.delete)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>dispatch (req, res, done)](#apidoc.element.express.Route.prototype.dispatch)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>get ()](#apidoc.element.express.Route.prototype.get)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>head ()](#apidoc.element.express.Route.prototype.head)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>link ()](#apidoc.element.express.Route.prototype.link)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>lock ()](#apidoc.element.express.Route.prototype.lock)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>m-search ()](#apidoc.element.express.Route.prototype.m-search)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>merge ()](#apidoc.element.express.Route.prototype.merge)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>mkactivity ()](#apidoc.element.express.Route.prototype.mkactivity)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>mkcalendar ()](#apidoc.element.express.Route.prototype.mkcalendar)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>mkcol ()](#apidoc.element.express.Route.prototype.mkcol)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>move ()](#apidoc.element.express.Route.prototype.move)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>notify ()](#apidoc.element.express.Route.prototype.notify)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>options ()](#apidoc.element.express.Route.prototype.options)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>patch ()](#apidoc.element.express.Route.prototype.patch)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>post ()](#apidoc.element.express.Route.prototype.post)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>propfind ()](#apidoc.element.express.Route.prototype.propfind)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>proppatch ()](#apidoc.element.express.Route.prototype.proppatch)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>purge ()](#apidoc.element.express.Route.prototype.purge)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>put ()](#apidoc.element.express.Route.prototype.put)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>rebind ()](#apidoc.element.express.Route.prototype.rebind)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>report ()](#apidoc.element.express.Route.prototype.report)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>search ()](#apidoc.element.express.Route.prototype.search)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>subscribe ()](#apidoc.element.express.Route.prototype.subscribe)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>trace ()](#apidoc.element.express.Route.prototype.trace)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>unbind ()](#apidoc.element.express.Route.prototype.unbind)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>unlink ()](#apidoc.element.express.Route.prototype.unlink)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>unlock ()](#apidoc.element.express.Route.prototype.unlock)
1.  [function <span class="apidocSignatureSpan">express.Route.prototype.</span>unsubscribe ()](#apidoc.element.express.Route.prototype.unsubscribe)

#### [module express.Router](#apidoc.module.express.Router)
1.  [function <span class="apidocSignatureSpan">express.</span>Router (options)](#apidoc.element.express.Router.Router)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>acl (path)](#apidoc.element.express.Router.acl)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>all (path)](#apidoc.element.express.Router.all)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>bind (path)](#apidoc.element.express.Router.bind)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>checkout (path)](#apidoc.element.express.Router.checkout)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>connect (path)](#apidoc.element.express.Router.connect)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>copy (path)](#apidoc.element.express.Router.copy)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>delete (path)](#apidoc.element.express.Router.delete)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>get (path)](#apidoc.element.express.Router.get)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>handle (req, res, out)](#apidoc.element.express.Router.handle)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>head (path)](#apidoc.element.express.Router.head)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>link (path)](#apidoc.element.express.Router.link)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>lock (path)](#apidoc.element.express.Router.lock)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>m-search (path)](#apidoc.element.express.Router.m-search)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>merge (path)](#apidoc.element.express.Router.merge)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>mkactivity (path)](#apidoc.element.express.Router.mkactivity)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>mkcalendar (path)](#apidoc.element.express.Router.mkcalendar)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>mkcol (path)](#apidoc.element.express.Router.mkcol)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>move (path)](#apidoc.element.express.Router.move)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>notify (path)](#apidoc.element.express.Router.notify)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>options (path)](#apidoc.element.express.Router.options)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>param (name, fn)](#apidoc.element.express.Router.param)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>patch (path)](#apidoc.element.express.Router.patch)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>post (path)](#apidoc.element.express.Router.post)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>process_params (layer, called, req, res, done)](#apidoc.element.express.Router.process_params)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>propfind (path)](#apidoc.element.express.Router.propfind)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>proppatch (path)](#apidoc.element.express.Router.proppatch)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>purge (path)](#apidoc.element.express.Router.purge)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>put (path)](#apidoc.element.express.Router.put)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>rebind (path)](#apidoc.element.express.Router.rebind)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>report (path)](#apidoc.element.express.Router.report)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>route (path)](#apidoc.element.express.Router.route)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>search (path)](#apidoc.element.express.Router.search)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>subscribe (path)](#apidoc.element.express.Router.subscribe)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>trace (path)](#apidoc.element.express.Router.trace)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>unbind (path)](#apidoc.element.express.Router.unbind)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>unlink (path)](#apidoc.element.express.Router.unlink)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>unlock (path)](#apidoc.element.express.Router.unlock)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>unsubscribe (path)](#apidoc.element.express.Router.unsubscribe)
1.  [function <span class="apidocSignatureSpan">express.Router.</span>use (fn)](#apidoc.element.express.Router.use)

#### [module express.application](#apidoc.module.express.application)
1.  [function <span class="apidocSignatureSpan">express.application.</span>acl (path)](#apidoc.element.express.application.acl)
1.  [function <span class="apidocSignatureSpan">express.application.</span>all (path)](#apidoc.element.express.application.all)
1.  [function <span class="apidocSignatureSpan">express.application.</span>bind (path)](#apidoc.element.express.application.bind)
1.  [function <span class="apidocSignatureSpan">express.application.</span>checkout (path)](#apidoc.element.express.application.checkout)
1.  [function <span class="apidocSignatureSpan">express.application.</span>connect (path)](#apidoc.element.express.application.connect)
1.  [function <span class="apidocSignatureSpan">express.application.</span>copy (path)](#apidoc.element.express.application.copy)
1.  [function <span class="apidocSignatureSpan">express.application.</span>defaultConfiguration ()](#apidoc.element.express.application.defaultConfiguration)
1.  [function <span class="apidocSignatureSpan">express.application.</span>del (arg0)](#apidoc.element.express.application.del)
1.  [function <span class="apidocSignatureSpan">express.application.</span>delete (path)](#apidoc.element.express.application.delete)
1.  [function <span class="apidocSignatureSpan">express.application.</span>disable (setting)](#apidoc.element.express.application.disable)
1.  [function <span class="apidocSignatureSpan">express.application.</span>disabled (setting)](#apidoc.element.express.application.disabled)
1.  [function <span class="apidocSignatureSpan">express.application.</span>enable (setting)](#apidoc.element.express.application.enable)
1.  [function <span class="apidocSignatureSpan">express.application.</span>enabled (setting)](#apidoc.element.express.application.enabled)
1.  [function <span class="apidocSignatureSpan">express.application.</span>engine (ext, fn)](#apidoc.element.express.application.engine)
1.  [function <span class="apidocSignatureSpan">express.application.</span>get (path)](#apidoc.element.express.application.get)
1.  [function <span class="apidocSignatureSpan">express.application.</span>handle (req, res, callback)](#apidoc.element.express.application.handle)
1.  [function <span class="apidocSignatureSpan">express.application.</span>head (path)](#apidoc.element.express.application.head)
1.  [function <span class="apidocSignatureSpan">express.application.</span>init ()](#apidoc.element.express.application.init)
1.  [function <span class="apidocSignatureSpan">express.application.</span>lazyrouter ()](#apidoc.element.express.application.lazyrouter)
1.  [function <span class="apidocSignatureSpan">express.application.</span>link (path)](#apidoc.element.express.application.link)
1.  [function <span class="apidocSignatureSpan">express.application.</span>listen ()](#apidoc.element.express.application.listen)
1.  [function <span class="apidocSignatureSpan">express.application.</span>lock (path)](#apidoc.element.express.application.lock)
1.  [function <span class="apidocSignatureSpan">express.application.</span>m-search (path)](#apidoc.element.express.application.m-search)
1.  [function <span class="apidocSignatureSpan">express.application.</span>merge (path)](#apidoc.element.express.application.merge)
1.  [function <span class="apidocSignatureSpan">express.application.</span>mkactivity (path)](#apidoc.element.express.application.mkactivity)
1.  [function <span class="apidocSignatureSpan">express.application.</span>mkcalendar (path)](#apidoc.element.express.application.mkcalendar)
1.  [function <span class="apidocSignatureSpan">express.application.</span>mkcol (path)](#apidoc.element.express.application.mkcol)
1.  [function <span class="apidocSignatureSpan">express.application.</span>move (path)](#apidoc.element.express.application.move)
1.  [function <span class="apidocSignatureSpan">express.application.</span>notify (path)](#apidoc.element.express.application.notify)
1.  [function <span class="apidocSignatureSpan">express.application.</span>options (path)](#apidoc.element.express.application.options)
1.  [function <span class="apidocSignatureSpan">express.application.</span>param (name, fn)](#apidoc.element.express.application.param)
1.  [function <span class="apidocSignatureSpan">express.application.</span>patch (path)](#apidoc.element.express.application.patch)
1.  [function <span class="apidocSignatureSpan">express.application.</span>path ()](#apidoc.element.express.application.path)
1.  [function <span class="apidocSignatureSpan">express.application.</span>post (path)](#apidoc.element.express.application.post)
1.  [function <span class="apidocSignatureSpan">express.application.</span>propfind (path)](#apidoc.element.express.application.propfind)
1.  [function <span class="apidocSignatureSpan">express.application.</span>proppatch (path)](#apidoc.element.express.application.proppatch)
1.  [function <span class="apidocSignatureSpan">express.application.</span>purge (path)](#apidoc.element.express.application.purge)
1.  [function <span class="apidocSignatureSpan">express.application.</span>put (path)](#apidoc.element.express.application.put)
1.  [function <span class="apidocSignatureSpan">express.application.</span>rebind (path)](#apidoc.element.express.application.rebind)
1.  [function <span class="apidocSignatureSpan">express.application.</span>render (name, options, callback)](#apidoc.element.express.application.render)
1.  [function <span class="apidocSignatureSpan">express.application.</span>report (path)](#apidoc.element.express.application.report)
1.  [function <span class="apidocSignatureSpan">express.application.</span>route (path)](#apidoc.element.express.application.route)
1.  [function <span class="apidocSignatureSpan">express.application.</span>search (path)](#apidoc.element.express.application.search)
1.  [function <span class="apidocSignatureSpan">express.application.</span>set (setting, val)](#apidoc.element.express.application.set)
1.  [function <span class="apidocSignatureSpan">express.application.</span>subscribe (path)](#apidoc.element.express.application.subscribe)
1.  [function <span class="apidocSignatureSpan">express.application.</span>trace (path)](#apidoc.element.express.application.trace)
1.  [function <span class="apidocSignatureSpan">express.application.</span>unbind (path)](#apidoc.element.express.application.unbind)
1.  [function <span class="apidocSignatureSpan">express.application.</span>unlink (path)](#apidoc.element.express.application.unlink)
1.  [function <span class="apidocSignatureSpan">express.application.</span>unlock (path)](#apidoc.element.express.application.unlock)
1.  [function <span class="apidocSignatureSpan">express.application.</span>unsubscribe (path)](#apidoc.element.express.application.unsubscribe)
1.  [function <span class="apidocSignatureSpan">express.application.</span>use (fn)](#apidoc.element.express.application.use)

#### [module express.request](#apidoc.module.express.request)
1.  [function <span class="apidocSignatureSpan">express.request.</span>accepts ()](#apidoc.element.express.request.accepts)
1.  [function <span class="apidocSignatureSpan">express.request.</span>acceptsCharset ()](#apidoc.element.express.request.acceptsCharset)
1.  [function <span class="apidocSignatureSpan">express.request.</span>acceptsCharsets ()](#apidoc.element.express.request.acceptsCharsets)
1.  [function <span class="apidocSignatureSpan">express.request.</span>acceptsEncoding ()](#apidoc.element.express.request.acceptsEncoding)
1.  [function <span class="apidocSignatureSpan">express.request.</span>acceptsEncodings ()](#apidoc.element.express.request.acceptsEncodings)
1.  [function <span class="apidocSignatureSpan">express.request.</span>acceptsLanguage ()](#apidoc.element.express.request.acceptsLanguage)
1.  [function <span class="apidocSignatureSpan">express.request.</span>acceptsLanguages ()](#apidoc.element.express.request.acceptsLanguages)
1.  [function <span class="apidocSignatureSpan">express.request.</span>get (name)](#apidoc.element.express.request.get)
1.  [function <span class="apidocSignatureSpan">express.request.</span>header (name)](#apidoc.element.express.request.header)
1.  [function <span class="apidocSignatureSpan">express.request.</span>is (types)](#apidoc.element.express.request.is)
1.  [function <span class="apidocSignatureSpan">express.request.</span>param (name, defaultValue)](#apidoc.element.express.request.param)
1.  [function <span class="apidocSignatureSpan">express.request.</span>range (size, options)](#apidoc.element.express.request.range)

#### [module express.response](#apidoc.module.express.response)
1.  [function <span class="apidocSignatureSpan">express.response.</span>append (field, val)](#apidoc.element.express.response.append)
1.  [function <span class="apidocSignatureSpan">express.response.</span>attachment (filename)](#apidoc.element.express.response.attachment)
1.  [function <span class="apidocSignatureSpan">express.response.</span>clearCookie (name, options)](#apidoc.element.express.response.clearCookie)
1.  [function <span class="apidocSignatureSpan">express.response.</span>contentType (type)](#apidoc.element.express.response.contentType)
1.  [function <span class="apidocSignatureSpan">express.response.</span>cookie (name, value, options)](#apidoc.element.express.response.cookie)
1.  [function <span class="apidocSignatureSpan">express.response.</span>download (path, filename, callback)](#apidoc.element.express.response.download)
1.  [function <span class="apidocSignatureSpan">express.response.</span>format (obj)](#apidoc.element.express.response.format)
1.  [function <span class="apidocSignatureSpan">express.response.</span>get (field)](#apidoc.element.express.response.get)
1.  [function <span class="apidocSignatureSpan">express.response.</span>header (field, val)](#apidoc.element.express.response.header)
1.  [function <span class="apidocSignatureSpan">express.response.</span>json (obj)](#apidoc.element.express.response.json)
1.  [function <span class="apidocSignatureSpan">express.response.</span>jsonp (obj)](#apidoc.element.express.response.jsonp)
1.  [function <span class="apidocSignatureSpan">express.response.</span>links (links)](#apidoc.element.express.response.links)
1.  [function <span class="apidocSignatureSpan">express.response.</span>location (url)](#apidoc.element.express.response.location)
1.  [function <span class="apidocSignatureSpan">express.response.</span>redirect (url)](#apidoc.element.express.response.redirect)
1.  [function <span class="apidocSignatureSpan">express.response.</span>render (view, options, callback)](#apidoc.element.express.response.render)
1.  [function <span class="apidocSignatureSpan">express.response.</span>send (body)](#apidoc.element.express.response.send)
1.  [function <span class="apidocSignatureSpan">express.response.</span>sendFile (path, options, callback)](#apidoc.element.express.response.sendFile)
1.  [function <span class="apidocSignatureSpan">express.response.</span>sendStatus (statusCode)](#apidoc.element.express.response.sendStatus)
1.  [function <span class="apidocSignatureSpan">express.response.</span>sendfile (arg0, arg1, arg2)](#apidoc.element.express.response.sendfile)
1.  [function <span class="apidocSignatureSpan">express.response.</span>set (field, val)](#apidoc.element.express.response.set)
1.  [function <span class="apidocSignatureSpan">express.response.</span>status (code)](#apidoc.element.express.response.status)
1.  [function <span class="apidocSignatureSpan">express.response.</span>type (type)](#apidoc.element.express.response.type)
1.  [function <span class="apidocSignatureSpan">express.response.</span>vary (field)](#apidoc.element.express.response.vary)

#### [module express.utils](#apidoc.module.express.utils)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>compileETag (val)](#apidoc.element.express.utils.compileETag)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>compileQueryParser (val)](#apidoc.element.express.utils.compileQueryParser)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>compileTrust (val)](#apidoc.element.express.utils.compileTrust)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>contentDisposition (arg0, arg1)](#apidoc.element.express.utils.contentDisposition)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>etag (body, encoding)](#apidoc.element.express.utils.etag)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>flatten (arg0, arg1)](#apidoc.element.express.utils.flatten)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>isAbsolute (path)](#apidoc.element.express.utils.isAbsolute)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>normalizeType (type)](#apidoc.element.express.utils.normalizeType)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>normalizeTypes (types)](#apidoc.element.express.utils.normalizeTypes)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>setCharset (type, charset)](#apidoc.element.express.utils.setCharset)
1.  [function <span class="apidocSignatureSpan">express.utils.</span>wetag (body, encoding)](#apidoc.element.express.utils.wetag)

#### [module express.view](#apidoc.module.express.view)
1.  [function <span class="apidocSignatureSpan">express.</span>view (name, options)](#apidoc.element.express.view.view)

#### [module express.view.prototype](#apidoc.module.express.view.prototype)
1.  [function <span class="apidocSignatureSpan">express.view.prototype.</span>lookup (name)](#apidoc.element.express.view.prototype.lookup)
1.  [function <span class="apidocSignatureSpan">express.view.prototype.</span>render (options, callback)](#apidoc.element.express.view.prototype.render)
1.  [function <span class="apidocSignatureSpan">express.view.prototype.</span>resolve (dir, file)](#apidoc.element.express.view.prototype.resolve)



# <a name="apidoc.module.express"></a>[module express](#apidoc.module.express)

#### <a name="apidoc.element.express.Route"></a>[function <span class="apidocSignatureSpan">express.</span>Route (path)](#apidoc.element.express.Route)
- description and source-code
```javascript
function Route(path) {
  this.path = path;
  this.stack = [];

  debug('new %o', path)

  // route handlers for various http methods
  this.methods = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router"></a>[function <span class="apidocSignatureSpan">express.</span>Router (options)](#apidoc.element.express.Router)
- description and source-code
```javascript
Router = function (options) {
  var opts = options || {};

  function router(req, res, next) {
    router.handle(req, res, next);
  }

  // mixin Router class functions
  setPrototypeOf(router, proto)

  router.params = {};
  router._params = [];
  router.caseSensitive = opts.caseSensitive;
  router.mergeParams = opts.mergeParams;
  router.strict = opts.strict;
  router.stack = [];

  return router;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.query"></a>[function <span class="apidocSignatureSpan">express.</span>query (options)](#apidoc.element.express.query)
- description and source-code
```javascript
function query(options) {
  var opts = Object.create(options || null);
  var queryparse = qs.parse;

  if (typeof options === 'function') {
    queryparse = options;
    opts = undefined;
  }

  if (opts !== undefined && opts.allowPrototypes === undefined) {
    // back-compat for qs module
    opts.allowPrototypes = true;
  }

  return function query(req, res, next){
    if (!req.query) {
      var val = parseUrl(req).query;
      req.query = queryparse(val, opts);
    }

    next();
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.static"></a>[function <span class="apidocSignatureSpan">express.</span>static (root, options)](#apidoc.element.express.static)
- description and source-code
```javascript
function serveStatic(root, options) {
  if (!root) {
    throw new TypeError('root path required')
  }

  if (typeof root !== 'string') {
    throw new TypeError('root path must be a string')
  }

  // copy options object
  var opts = Object.create(options || null)

  // fall-though
  var fallthrough = opts.fallthrough !== false

  // default redirect
  var redirect = opts.redirect !== false

  // headers listener
  var setHeaders = opts.setHeaders

  if (setHeaders && typeof setHeaders !== 'function') {
    throw new TypeError('option setHeaders must be function')
  }

  // setup options for send
  opts.maxage = opts.maxage || opts.maxAge || 0
  opts.root = resolve(root)

  // construct directory listener
  var onDirectory = redirect
    ? createRedirectDirectoryListener()
    : createNotFoundDirectoryListener()

  return function serveStatic (req, res, next) {
    if (req.method !== 'GET' && req.method !== 'HEAD') {
      if (fallthrough) {
        return next()
      }

      // method not allowed
      res.statusCode = 405
      res.setHeader('Allow', 'GET, HEAD')
      res.setHeader('Content-Length', '0')
      res.end()
      return
    }

    var forwardError = !fallthrough
    var originalUrl = parseUrl.original(req)
    var path = parseUrl(req).pathname

    // make sure redirect occurs at mount
    if (path === '/' && originalUrl.pathname.substr(-1) !== '/') {
      path = ''
    }

    // create send stream
    var stream = send(req, path, opts)

    // add directory handler
    stream.on('directory', onDirectory)

    // add headers listener
    if (setHeaders) {
      stream.on('headers', setHeaders)
    }

    // add file listener for fallthrough
    if (fallthrough) {
      stream.on('file', function onFile () {
        // once file is determined, always forward error
        forwardError = true
      })
    }

    // forward errors
    stream.on('error', function error (err) {
      if (forwardError || !(err.statusCode < 500)) {
        next(err)
        return
      }

      next()
    })

    // pipe
    stream.pipe(res)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.view"></a>[function <span class="apidocSignatureSpan">express.</span>view (name, options)](#apidoc.element.express.view)
- description and source-code
```javascript
function View(name, options) {
  var opts = options || {};

  this.defaultEngine = opts.defaultEngine;
  this.ext = extname(name);
  this.name = name;
  this.root = opts.root;

  if (!this.ext && !this.defaultEngine) {
    throw new Error('No default engine was specified and no extension was provided.');
  }

  var fileName = name;

  if (!this.ext) {
    // get extension from default engine name
    this.ext = this.defaultEngine[0] !== '.'
      ? '.' + this.defaultEngine
      : this.defaultEngine;

    fileName += this.ext;
  }

  if (!opts.engines[this.ext]) {
    // load engine
    var mod = this.ext.substr(1)
    debug('require "%s"', mod)
    opts.engines[this.ext] = require(mod).__express
  }

  // store loaded engine
  this.engine = opts.engines[this.ext];

  // lookup path
  this.path = this.lookup(fileName);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.Route"></a>[module express.Route](#apidoc.module.express.Route)

#### <a name="apidoc.element.express.Route.Route"></a>[function <span class="apidocSignatureSpan">express.</span>Route (path)](#apidoc.element.express.Route.Route)
- description and source-code
```javascript
function Route(path) {
  this.path = path;
  this.stack = [];

  debug('new %o', path)

  // route handlers for various http methods
  this.methods = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.Route.prototype"></a>[module express.Route.prototype](#apidoc.module.express.Route.prototype)

#### <a name="apidoc.element.express.Route.prototype._handles_method"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>_handles_method (method)](#apidoc.element.express.Route.prototype._handles_method)
- description and source-code
```javascript
function _handles_method(method) {
  if (this.methods._all) {
    return true;
  }

  var name = method.toLowerCase();

  if (name === 'head' && !this.methods['head']) {
    name = 'get';
  }

  return Boolean(this.methods[name]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype._options"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>_options ()](#apidoc.element.express.Route.prototype._options)
- description and source-code
```javascript
function _options() {
  var methods = Object.keys(this.methods);

  // append automatic head
  if (this.methods.get && !this.methods.head) {
    methods.push('head');
  }

  for (var i = 0; i < methods.length; i++) {
    // make upper case
    methods[i] = methods[i].toUpperCase();
  }

  return methods;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.acl"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>acl ()](#apidoc.element.express.Route.prototype.acl)
- description and source-code
```javascript
acl = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.all"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>all ()](#apidoc.element.express.Route.prototype.all)
- description and source-code
```javascript
function all() {
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.all() requires callback functions but got a ' + type;
      throw new TypeError(msg);
    }

    var layer = Layer('/', {}, handle);
    layer.method = undefined;

    this.methods._all = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.bind"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>bind ()](#apidoc.element.express.Route.prototype.bind)
- description and source-code
```javascript
bind = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.checkout"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>checkout ()](#apidoc.element.express.Route.prototype.checkout)
- description and source-code
```javascript
checkout = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.connect"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>connect ()](#apidoc.element.express.Route.prototype.connect)
- description and source-code
```javascript
connect = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.copy"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>copy ()](#apidoc.element.express.Route.prototype.copy)
- description and source-code
```javascript
copy = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.delete"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>delete ()](#apidoc.element.express.Route.prototype.delete)
- description and source-code
```javascript
delete = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.dispatch"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>dispatch (req, res, done)](#apidoc.element.express.Route.prototype.dispatch)
- description and source-code
```javascript
function dispatch(req, res, done) {
  var idx = 0;
  var stack = this.stack;
  if (stack.length === 0) {
    return done();
  }

  var method = req.method.toLowerCase();
  if (method === 'head' && !this.methods['head']) {
    method = 'get';
  }

  req.route = this;

  next();

  function next(err) {
    // signal to exit route
    if (err && err === 'route') {
      return done();
    }

    // signal to exit router
    if (err && err === 'router') {
      return done(err)
    }

    var layer = stack[idx++];
    if (!layer) {
      return done(err);
    }

    if (layer.method && layer.method !== method) {
      return next(err);
    }

    if (err) {
      layer.handle_error(err, req, res, next);
    } else {
      layer.handle_request(req, res, next);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.get"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>get ()](#apidoc.element.express.Route.prototype.get)
- description and source-code
```javascript
get = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
...
  [![Windows Build][appveyor-image]][appveyor-url]
  [![Test Coverage][coveralls-image]][coveralls-url]

'''js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
'''

## Installation
...
```

#### <a name="apidoc.element.express.Route.prototype.head"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>head ()](#apidoc.element.express.Route.prototype.head)
- description and source-code
```javascript
head = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.link"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>link ()](#apidoc.element.express.Route.prototype.link)
- description and source-code
```javascript
link = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.lock"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>lock ()](#apidoc.element.express.Route.prototype.lock)
- description and source-code
```javascript
lock = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.m-search"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>m-search ()](#apidoc.element.express.Route.prototype.m-search)
- description and source-code
```javascript
m-search = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.merge"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>merge ()](#apidoc.element.express.Route.prototype.merge)
- description and source-code
```javascript
merge = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.mkactivity"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>mkactivity ()](#apidoc.element.express.Route.prototype.mkactivity)
- description and source-code
```javascript
mkactivity = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.mkcalendar"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>mkcalendar ()](#apidoc.element.express.Route.prototype.mkcalendar)
- description and source-code
```javascript
mkcalendar = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.mkcol"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>mkcol ()](#apidoc.element.express.Route.prototype.mkcol)
- description and source-code
```javascript
mkcol = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.move"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>move ()](#apidoc.element.express.Route.prototype.move)
- description and source-code
```javascript
move = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.notify"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>notify ()](#apidoc.element.express.Route.prototype.notify)
- description and source-code
```javascript
notify = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.options"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>options ()](#apidoc.element.express.Route.prototype.options)
- description and source-code
```javascript
options = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.patch"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>patch ()](#apidoc.element.express.Route.prototype.patch)
- description and source-code
```javascript
patch = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.post"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>post ()](#apidoc.element.express.Route.prototype.post)
- description and source-code
```javascript
post = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.propfind"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>propfind ()](#apidoc.element.express.Route.prototype.propfind)
- description and source-code
```javascript
propfind = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.proppatch"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>proppatch ()](#apidoc.element.express.Route.prototype.proppatch)
- description and source-code
```javascript
proppatch = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.purge"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>purge ()](#apidoc.element.express.Route.prototype.purge)
- description and source-code
```javascript
purge = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.put"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>put ()](#apidoc.element.express.Route.prototype.put)
- description and source-code
```javascript
put = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.rebind"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>rebind ()](#apidoc.element.express.Route.prototype.rebind)
- description and source-code
```javascript
rebind = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.report"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>report ()](#apidoc.element.express.Route.prototype.report)
- description and source-code
```javascript
report = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.search"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>search ()](#apidoc.element.express.Route.prototype.search)
- description and source-code
```javascript
search = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.subscribe"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>subscribe ()](#apidoc.element.express.Route.prototype.subscribe)
- description and source-code
```javascript
subscribe = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.trace"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>trace ()](#apidoc.element.express.Route.prototype.trace)
- description and source-code
```javascript
trace = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.unbind"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>unbind ()](#apidoc.element.express.Route.prototype.unbind)
- description and source-code
```javascript
unbind = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.unlink"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>unlink ()](#apidoc.element.express.Route.prototype.unlink)
- description and source-code
```javascript
unlink = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.unlock"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>unlock ()](#apidoc.element.express.Route.prototype.unlock)
- description and source-code
```javascript
unlock = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Route.prototype.unsubscribe"></a>[function <span class="apidocSignatureSpan">express.Route.prototype.</span>unsubscribe ()](#apidoc.element.express.Route.prototype.unsubscribe)
- description and source-code
```javascript
unsubscribe = function (){
  var handles = flatten(slice.call(arguments));

  for (var i = 0; i < handles.length; i++) {
    var handle = handles[i];

    if (typeof handle !== 'function') {
      var type = toString.call(handle);
      var msg = 'Route.' + method + '() requires callback functions but got a ' + type;
      throw new Error(msg);
    }

    debug('%s %o', method, this.path)

    var layer = Layer('/', {}, handle);
    layer.method = method;

    this.methods[method] = true;
    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.Router"></a>[module express.Router](#apidoc.module.express.Router)

#### <a name="apidoc.element.express.Router.Router"></a>[function <span class="apidocSignatureSpan">express.</span>Router (options)](#apidoc.element.express.Router.Router)
- description and source-code
```javascript
Router = function (options) {
  var opts = options || {};

  function router(req, res, next) {
    router.handle(req, res, next);
  }

  // mixin Router class functions
  setPrototypeOf(router, proto)

  router.params = {};
  router._params = [];
  router.caseSensitive = opts.caseSensitive;
  router.mergeParams = opts.mergeParams;
  router.strict = opts.strict;
  router.stack = [];

  return router;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.acl"></a>[function <span class="apidocSignatureSpan">express.Router.</span>acl (path)](#apidoc.element.express.Router.acl)
- description and source-code
```javascript
acl = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.all"></a>[function <span class="apidocSignatureSpan">express.Router.</span>all (path)](#apidoc.element.express.Router.all)
- description and source-code
```javascript
all = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.bind"></a>[function <span class="apidocSignatureSpan">express.Router.</span>bind (path)](#apidoc.element.express.Router.bind)
- description and source-code
```javascript
bind = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.checkout"></a>[function <span class="apidocSignatureSpan">express.Router.</span>checkout (path)](#apidoc.element.express.Router.checkout)
- description and source-code
```javascript
checkout = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.connect"></a>[function <span class="apidocSignatureSpan">express.Router.</span>connect (path)](#apidoc.element.express.Router.connect)
- description and source-code
```javascript
connect = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.copy"></a>[function <span class="apidocSignatureSpan">express.Router.</span>copy (path)](#apidoc.element.express.Router.copy)
- description and source-code
```javascript
copy = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.delete"></a>[function <span class="apidocSignatureSpan">express.Router.</span>delete (path)](#apidoc.element.express.Router.delete)
- description and source-code
```javascript
delete = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.get"></a>[function <span class="apidocSignatureSpan">express.Router.</span>get (path)](#apidoc.element.express.Router.get)
- description and source-code
```javascript
get = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
...
  [![Windows Build][appveyor-image]][appveyor-url]
  [![Test Coverage][coveralls-image]][coveralls-url]

'''js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
'''

## Installation
...
```

#### <a name="apidoc.element.express.Router.handle"></a>[function <span class="apidocSignatureSpan">express.Router.</span>handle (req, res, out)](#apidoc.element.express.Router.handle)
- description and source-code
```javascript
function handle(req, res, out) {
  var self = this;

  debug('dispatching %s %s', req.method, req.url);

  var idx = 0;
  var protohost = getProtohost(req.url) || ''
  var removed = '';
  var slashAdded = false;
  var paramcalled = {};

  // store options for OPTIONS request
  // only used if OPTIONS request
  var options = [];

  // middleware and routes
  var stack = self.stack;

  // manage inter-router variables
  var parentParams = req.params;
  var parentUrl = req.baseUrl || '';
  var done = restore(out, req, 'baseUrl', 'next', 'params');

  // setup next layer
  req.next = next;

  // for options requests, respond with a default if nothing else responds
  if (req.method === 'OPTIONS') {
    done = wrap(done, function(old, err) {
      if (err || options.length === 0) return old(err);
      sendOptionsResponse(res, options, old);
    });
  }

  // setup basic req values
  req.baseUrl = parentUrl;
  req.originalUrl = req.originalUrl || req.url;

  next();

  function next(err) {
    var layerError = err === 'route'
      ? null
      : err;

    // remove added slash
    if (slashAdded) {
      req.url = req.url.substr(1);
      slashAdded = false;
    }

    // restore altered req.url
    if (removed.length !== 0) {
      req.baseUrl = parentUrl;
      req.url = protohost + removed + req.url.substr(protohost.length);
      removed = '';
    }

    // signal to exit router
    if (layerError === 'router') {
      setImmediate(done, null)
      return
    }

    // no more matching layers
    if (idx >= stack.length) {
      setImmediate(done, layerError);
      return;
    }

    // get pathname of request
    var path = getPathname(req);

    if (path == null) {
      return done(layerError);
    }

    // find next matching layer
    var layer;
    var match;
    var route;

    while (match !== true && idx < stack.length) {
      layer = stack[idx++];
      match = matchLayer(layer, path);
      route = layer.route;

      if (typeof match !== 'boolean') {
        // hold on to layerError
        layerError = layerError || match;
      }

      if (match !== true) {
        continue;
      }

      if (!route) {
        // process non-route handlers normally
        continue;
      }

      if (layerError) {
        // routes do not match with a pending error
        match = false;
        continue;
      }

      var method = req.method;
      var has_method = route._handles_method(method);

      // build up automatic options response
      if (!has_method && method === 'OPTIONS') {
        appendMethods(options, route._options());
      }

      // don't even bother matching route
      if (!has_method && method !== 'HEAD') {
        match = false;
        continue;
      }
    }

    // no match
    if (match !== true) {
      return done(layerError);
    }

    // store route for dispatch on change
    if (route) {
      req.route = route;
    }

    // Capture one-time layer values
    req.params = self.mergeParams
      ? mergeParams(layer.params, parentParams)
      : layer.params;
    var layerPath = layer.path;

    // this should be done for the layer
    self.process_params(layer, paramcalled, req, res, function (err) {
      if (err) {
        return next(layerError || err);
      }

      if (route) {
        return layer.handle_request(req, res, next);
      }

      trim_prefix(layer, layerError, layerPath, path);
    });
  }

  function trim_prefix(layer, layerError, layerPath, path) {
    if (layerPath.length !== 0) {
      // Validate path breaks on a path separator
      var c = path[layerPath.length]
      if (c && c !== '/' && c !== '.') return next(layerError)

      // Trim off the part of the url that matches the route
      // middleware (.use stuff) needs to have the path stripped
      debug('trim prefix (%s) from url %s', layerPath, req.url);
      removed = layerPath;
      req.url = protohost + req.url.substr(protohost.length + removed.length);

      // Ensure leading slash
      if (!protohost && req.url[0] !== '/') {
        req.url = '/' + req.url;
        slashAdded = true; ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.head"></a>[function <span class="apidocSignatureSpan">express.Router.</span>head (path)](#apidoc.element.express.Router.head)
- description and source-code
```javascript
head = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.link"></a>[function <span class="apidocSignatureSpan">express.Router.</span>link (path)](#apidoc.element.express.Router.link)
- description and source-code
```javascript
link = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.lock"></a>[function <span class="apidocSignatureSpan">express.Router.</span>lock (path)](#apidoc.element.express.Router.lock)
- description and source-code
```javascript
lock = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.m-search"></a>[function <span class="apidocSignatureSpan">express.Router.</span>m-search (path)](#apidoc.element.express.Router.m-search)
- description and source-code
```javascript
m-search = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.merge"></a>[function <span class="apidocSignatureSpan">express.Router.</span>merge (path)](#apidoc.element.express.Router.merge)
- description and source-code
```javascript
merge = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.mkactivity"></a>[function <span class="apidocSignatureSpan">express.Router.</span>mkactivity (path)](#apidoc.element.express.Router.mkactivity)
- description and source-code
```javascript
mkactivity = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.mkcalendar"></a>[function <span class="apidocSignatureSpan">express.Router.</span>mkcalendar (path)](#apidoc.element.express.Router.mkcalendar)
- description and source-code
```javascript
mkcalendar = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.mkcol"></a>[function <span class="apidocSignatureSpan">express.Router.</span>mkcol (path)](#apidoc.element.express.Router.mkcol)
- description and source-code
```javascript
mkcol = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.move"></a>[function <span class="apidocSignatureSpan">express.Router.</span>move (path)](#apidoc.element.express.Router.move)
- description and source-code
```javascript
move = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.notify"></a>[function <span class="apidocSignatureSpan">express.Router.</span>notify (path)](#apidoc.element.express.Router.notify)
- description and source-code
```javascript
notify = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.options"></a>[function <span class="apidocSignatureSpan">express.Router.</span>options (path)](#apidoc.element.express.Router.options)
- description and source-code
```javascript
options = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.param"></a>[function <span class="apidocSignatureSpan">express.Router.</span>param (name, fn)](#apidoc.element.express.Router.param)
- description and source-code
```javascript
function param(name, fn) {
  // param logic
  if (typeof name === 'function') {
    deprecate('router.param(fn): Refactor to use path params');
    this._params.push(name);
    return;
  }

  // apply param functions
  var params = this._params;
  var len = params.length;
  var ret;

  if (name[0] === ':') {
    deprecate('router.param(' + JSON.stringify(name) + ', fn): Use router.param(' + JSON.stringify(name.substr(1)) + ', fn) instead
');
    name = name.substr(1);
  }

  for (var i = 0; i < len; ++i) {
    if (ret = params[i](name, fn)) {
      fn = ret;
    }
  }

  // ensure we end up with a
  // middleware function
  if ('function' !== typeof fn) {
    throw new Error('invalid param() call for ' + name + ', got ' + fn);
  }

  (this.params[name] = this.params[name] || []).push(fn);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.patch"></a>[function <span class="apidocSignatureSpan">express.Router.</span>patch (path)](#apidoc.element.express.Router.patch)
- description and source-code
```javascript
patch = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.post"></a>[function <span class="apidocSignatureSpan">express.Router.</span>post (path)](#apidoc.element.express.Router.post)
- description and source-code
```javascript
post = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.process_params"></a>[function <span class="apidocSignatureSpan">express.Router.</span>process_params (layer, called, req, res, done)](#apidoc.element.express.Router.process_params)
- description and source-code
```javascript
function process_params(layer, called, req, res, done) {
  var params = this.params;

  // captured parameters from the layer, keys and values
  var keys = layer.keys;

  // fast track
  if (!keys || keys.length === 0) {
    return done();
  }

  var i = 0;
  var name;
  var paramIndex = 0;
  var key;
  var paramVal;
  var paramCallbacks;
  var paramCalled;

  // process params in order
  // param callbacks can be async
  function param(err) {
    if (err) {
      return done(err);
    }

    if (i >= keys.length ) {
      return done();
    }

    paramIndex = 0;
    key = keys[i++];
    name = key.name;
    paramVal = req.params[name];
    paramCallbacks = params[name];
    paramCalled = called[name];

    if (paramVal === undefined || !paramCallbacks) {
      return param();
    }

    // param previously called with same value or error occurred
    if (paramCalled && (paramCalled.match === paramVal
      || (paramCalled.error && paramCalled.error !== 'route'))) {
      // restore value
      req.params[name] = paramCalled.value;

      // next param
      return param(paramCalled.error);
    }

    called[name] = paramCalled = {
      error: null,
      match: paramVal,
      value: paramVal
    };

    paramCallback();
  }

  // single param callbacks
  function paramCallback(err) {
    var fn = paramCallbacks[paramIndex++];

    // store updated value
    paramCalled.value = req.params[key.name];

    if (err) {
      // store error
      paramCalled.error = err;
      param(err);
      return;
    }

    if (!fn) return param();

    try {
      fn(req, res, paramCallback, paramVal, key.name);
    } catch (e) {
      paramCallback(e);
    }
  }

  param();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.propfind"></a>[function <span class="apidocSignatureSpan">express.Router.</span>propfind (path)](#apidoc.element.express.Router.propfind)
- description and source-code
```javascript
propfind = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.proppatch"></a>[function <span class="apidocSignatureSpan">express.Router.</span>proppatch (path)](#apidoc.element.express.Router.proppatch)
- description and source-code
```javascript
proppatch = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.purge"></a>[function <span class="apidocSignatureSpan">express.Router.</span>purge (path)](#apidoc.element.express.Router.purge)
- description and source-code
```javascript
purge = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.put"></a>[function <span class="apidocSignatureSpan">express.Router.</span>put (path)](#apidoc.element.express.Router.put)
- description and source-code
```javascript
put = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.rebind"></a>[function <span class="apidocSignatureSpan">express.Router.</span>rebind (path)](#apidoc.element.express.Router.rebind)
- description and source-code
```javascript
rebind = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.report"></a>[function <span class="apidocSignatureSpan">express.Router.</span>report (path)](#apidoc.element.express.Router.report)
- description and source-code
```javascript
report = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.route"></a>[function <span class="apidocSignatureSpan">express.Router.</span>route (path)](#apidoc.element.express.Router.route)
- description and source-code
```javascript
function route(path) {
  var route = new Route(path);

  var layer = new Layer(path, {
    sensitive: this.caseSensitive,
    strict: this.strict,
    end: true
  }, route.dispatch.bind(route));

  layer.route = route;

  this.stack.push(layer);
  return route;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.search"></a>[function <span class="apidocSignatureSpan">express.Router.</span>search (path)](#apidoc.element.express.Router.search)
- description and source-code
```javascript
search = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.subscribe"></a>[function <span class="apidocSignatureSpan">express.Router.</span>subscribe (path)](#apidoc.element.express.Router.subscribe)
- description and source-code
```javascript
subscribe = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.trace"></a>[function <span class="apidocSignatureSpan">express.Router.</span>trace (path)](#apidoc.element.express.Router.trace)
- description and source-code
```javascript
trace = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.unbind"></a>[function <span class="apidocSignatureSpan">express.Router.</span>unbind (path)](#apidoc.element.express.Router.unbind)
- description and source-code
```javascript
unbind = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.unlink"></a>[function <span class="apidocSignatureSpan">express.Router.</span>unlink (path)](#apidoc.element.express.Router.unlink)
- description and source-code
```javascript
unlink = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.unlock"></a>[function <span class="apidocSignatureSpan">express.Router.</span>unlock (path)](#apidoc.element.express.Router.unlock)
- description and source-code
```javascript
unlock = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.unsubscribe"></a>[function <span class="apidocSignatureSpan">express.Router.</span>unsubscribe (path)](#apidoc.element.express.Router.unsubscribe)
- description and source-code
```javascript
unsubscribe = function (path){
  var route = this.route(path)
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.Router.use"></a>[function <span class="apidocSignatureSpan">express.Router.</span>use (fn)](#apidoc.element.express.Router.use)
- description and source-code
```javascript
function use(fn) {
  var offset = 0;
  var path = '/';

  // default path to '/'
  // disambiguate router.use([fn])
  if (typeof fn !== 'function') {
    var arg = fn;

    while (Array.isArray(arg) && arg.length !== 0) {
      arg = arg[0];
    }

    // first arg is the path
    if (typeof arg !== 'function') {
      offset = 1;
      path = fn;
    }
  }

  var callbacks = flatten(slice.call(arguments, offset));

  if (callbacks.length === 0) {
    throw new TypeError('Router.use() requires middleware functions');
  }

  for (var i = 0; i < callbacks.length; i++) {
    var fn = callbacks[i];

    if (typeof fn !== 'function') {
      throw new TypeError('Router.use() requires middleware function but got a ' + gettype(fn));
    }

    // add the middleware
    debug('use %o %s', path, fn.name || '<anonymous>')

    var layer = new Layer(path, {
      sensitive: this.caseSensitive,
      strict: false,
      end: false
    }, fn);

    layer.route = undefined;

    this.stack.push(layer);
  }

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.application"></a>[module express.application](#apidoc.module.express.application)

#### <a name="apidoc.element.express.application.acl"></a>[function <span class="apidocSignatureSpan">express.application.</span>acl (path)](#apidoc.element.express.application.acl)
- description and source-code
```javascript
acl = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.all"></a>[function <span class="apidocSignatureSpan">express.application.</span>all (path)](#apidoc.element.express.application.all)
- description and source-code
```javascript
function all(path) {
  this.lazyrouter();

  var route = this._router.route(path);
  var args = slice.call(arguments, 1);

  for (var i = 0; i < methods.length; i++) {
    route[methods[i]].apply(route, args);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.bind"></a>[function <span class="apidocSignatureSpan">express.application.</span>bind (path)](#apidoc.element.express.application.bind)
- description and source-code
```javascript
bind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.checkout"></a>[function <span class="apidocSignatureSpan">express.application.</span>checkout (path)](#apidoc.element.express.application.checkout)
- description and source-code
```javascript
checkout = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.connect"></a>[function <span class="apidocSignatureSpan">express.application.</span>connect (path)](#apidoc.element.express.application.connect)
- description and source-code
```javascript
connect = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.copy"></a>[function <span class="apidocSignatureSpan">express.application.</span>copy (path)](#apidoc.element.express.application.copy)
- description and source-code
```javascript
copy = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.defaultConfiguration"></a>[function <span class="apidocSignatureSpan">express.application.</span>defaultConfiguration ()](#apidoc.element.express.application.defaultConfiguration)
- description and source-code
```javascript
function defaultConfiguration() {
  var env = process.env.NODE_ENV || 'development';

  // default settings
  this.enable('x-powered-by');
  this.set('etag', 'weak');
  this.set('env', env);
  this.set('query parser', 'extended');
  this.set('subdomain offset', 2);
  this.set('trust proxy', false);

  // trust proxy inherit back-compat
  Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
    configurable: true,
    value: true
  });

  debug('booting in %s mode', env);

  this.on('mount', function onmount(parent) {
    // inherit trust proxy
    if (this.settings[trustProxyDefaultSymbol] === true
      && typeof parent.settings['trust proxy fn'] === 'function') {
      delete this.settings['trust proxy'];
      delete this.settings['trust proxy fn'];
    }

    // inherit protos
    setPrototyeOf(this.request, parent.request)
    setPrototyeOf(this.response, parent.response)
    setPrototyeOf(this.engines, parent.engines)
    setPrototyeOf(this.settings, parent.settings)
  });

  // setup locals
  this.locals = Object.create(null);

  // top-most app is mounted at /
  this.mountpath = '/';

  // default locals
  this.locals.settings = this.settings;

  // default configuration
  this.set('view', View);
  this.set('views', resolve('views'));
  this.set('jsonp callback name', 'callback');

  if (env === 'production') {
    this.enable('view cache');
  }

  Object.defineProperty(this, 'router', {
    get: function() {
      throw new Error('\'app.router\' is deprecated!\nPlease see the 3.x to 4.x migration guide for details on how to update your
 app.');
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.del"></a>[function <span class="apidocSignatureSpan">express.application.</span>del (arg0)](#apidoc.element.express.application.del)
- description and source-code
```javascript
del = function (arg0) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.delete"></a>[function <span class="apidocSignatureSpan">express.application.</span>delete (path)](#apidoc.element.express.application.delete)
- description and source-code
```javascript
delete = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.disable"></a>[function <span class="apidocSignatureSpan">express.application.</span>disable (setting)](#apidoc.element.express.application.disable)
- description and source-code
```javascript
function disable(setting) {
  return this.set(setting, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.disabled"></a>[function <span class="apidocSignatureSpan">express.application.</span>disabled (setting)](#apidoc.element.express.application.disabled)
- description and source-code
```javascript
function disabled(setting) {
  return !this.set(setting);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.enable"></a>[function <span class="apidocSignatureSpan">express.application.</span>enable (setting)](#apidoc.element.express.application.enable)
- description and source-code
```javascript
function enable(setting) {
  return this.set(setting, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.enabled"></a>[function <span class="apidocSignatureSpan">express.application.</span>enabled (setting)](#apidoc.element.express.application.enabled)
- description and source-code
```javascript
function enabled(setting) {
  return Boolean(this.set(setting));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.engine"></a>[function <span class="apidocSignatureSpan">express.application.</span>engine (ext, fn)](#apidoc.element.express.application.engine)
- description and source-code
```javascript
function engine(ext, fn) {
  if (typeof fn !== 'function') {
    throw new Error('callback function required');
  }

  // get file extension
  var extension = ext[0] !== '.'
    ? '.' + ext
    : ext;

  // store engine
  this.engines[extension] = fn;

  return this;
}
```
- example usage
```shell
...
* @param {object} options
* @param {function} callback
* @private
*/

View.prototype.render = function render(options, callback) {
 debug('render "%s"', this.path);
 this.engine(this.path, options, callback);
};

/**
* Resolve the file within the given directory.
*
* @param {string} dir
* @param {string} file
...
```

#### <a name="apidoc.element.express.application.get"></a>[function <span class="apidocSignatureSpan">express.application.</span>get (path)](#apidoc.element.express.application.get)
- description and source-code
```javascript
get = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
...
  [![Windows Build][appveyor-image]][appveyor-url]
  [![Test Coverage][coveralls-image]][coveralls-url]

'''js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
'''

## Installation
...
```

#### <a name="apidoc.element.express.application.handle"></a>[function <span class="apidocSignatureSpan">express.application.</span>handle (req, res, callback)](#apidoc.element.express.application.handle)
- description and source-code
```javascript
function handle(req, res, callback) {
  var router = this._router;

  // final handler
  var done = callback || finalhandler(req, res, {
    env: this.get('env'),
    onerror: logerror.bind(this)
  });

  // no routes
  if (!router) {
    debug('no routes defined on app');
    done();
    return;
  }

  router.handle(req, res, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.head"></a>[function <span class="apidocSignatureSpan">express.application.</span>head (path)](#apidoc.element.express.application.head)
- description and source-code
```javascript
head = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.init"></a>[function <span class="apidocSignatureSpan">express.application.</span>init ()](#apidoc.element.express.application.init)
- description and source-code
```javascript
function init() {
  this.cache = {};
  this.engines = {};
  this.settings = {};

  this.defaultConfiguration();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.lazyrouter"></a>[function <span class="apidocSignatureSpan">express.application.</span>lazyrouter ()](#apidoc.element.express.application.lazyrouter)
- description and source-code
```javascript
function lazyrouter() {
  if (!this._router) {
    this._router = new Router({
      caseSensitive: this.enabled('case sensitive routing'),
      strict: this.enabled('strict routing')
    });

    this._router.use(query(this.get('query parser fn')));
    this._router.use(middleware.init(this));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.link"></a>[function <span class="apidocSignatureSpan">express.application.</span>link (path)](#apidoc.element.express.application.link)
- description and source-code
```javascript
link = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.listen"></a>[function <span class="apidocSignatureSpan">express.application.</span>listen ()](#apidoc.element.express.application.listen)
- description and source-code
```javascript
function listen() {
  var server = http.createServer(this);
  return server.listen.apply(server, arguments);
}
```
- example usage
```shell
...
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
'''

## Installation

'''bash
$ npm install express
'''
...
```

#### <a name="apidoc.element.express.application.lock"></a>[function <span class="apidocSignatureSpan">express.application.</span>lock (path)](#apidoc.element.express.application.lock)
- description and source-code
```javascript
lock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.m-search"></a>[function <span class="apidocSignatureSpan">express.application.</span>m-search (path)](#apidoc.element.express.application.m-search)
- description and source-code
```javascript
m-search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.merge"></a>[function <span class="apidocSignatureSpan">express.application.</span>merge (path)](#apidoc.element.express.application.merge)
- description and source-code
```javascript
merge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.mkactivity"></a>[function <span class="apidocSignatureSpan">express.application.</span>mkactivity (path)](#apidoc.element.express.application.mkactivity)
- description and source-code
```javascript
mkactivity = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.mkcalendar"></a>[function <span class="apidocSignatureSpan">express.application.</span>mkcalendar (path)](#apidoc.element.express.application.mkcalendar)
- description and source-code
```javascript
mkcalendar = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.mkcol"></a>[function <span class="apidocSignatureSpan">express.application.</span>mkcol (path)](#apidoc.element.express.application.mkcol)
- description and source-code
```javascript
mkcol = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.move"></a>[function <span class="apidocSignatureSpan">express.application.</span>move (path)](#apidoc.element.express.application.move)
- description and source-code
```javascript
move = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.notify"></a>[function <span class="apidocSignatureSpan">express.application.</span>notify (path)](#apidoc.element.express.application.notify)
- description and source-code
```javascript
notify = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.options"></a>[function <span class="apidocSignatureSpan">express.application.</span>options (path)](#apidoc.element.express.application.options)
- description and source-code
```javascript
options = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.param"></a>[function <span class="apidocSignatureSpan">express.application.</span>param (name, fn)](#apidoc.element.express.application.param)
- description and source-code
```javascript
function param(name, fn) {
  this.lazyrouter();

  if (Array.isArray(name)) {
    for (var i = 0; i < name.length; i++) {
      this.param(name[i], fn);
    }

    return this;
  }

  this._router.param(name, fn);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.patch"></a>[function <span class="apidocSignatureSpan">express.application.</span>patch (path)](#apidoc.element.express.application.patch)
- description and source-code
```javascript
patch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.path"></a>[function <span class="apidocSignatureSpan">express.application.</span>path ()](#apidoc.element.express.application.path)
- description and source-code
```javascript
function path() {
  return this.parent
    ? this.parent.path() + this.mountpath
    : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.post"></a>[function <span class="apidocSignatureSpan">express.application.</span>post (path)](#apidoc.element.express.application.post)
- description and source-code
```javascript
post = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.propfind"></a>[function <span class="apidocSignatureSpan">express.application.</span>propfind (path)](#apidoc.element.express.application.propfind)
- description and source-code
```javascript
propfind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.proppatch"></a>[function <span class="apidocSignatureSpan">express.application.</span>proppatch (path)](#apidoc.element.express.application.proppatch)
- description and source-code
```javascript
proppatch = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.purge"></a>[function <span class="apidocSignatureSpan">express.application.</span>purge (path)](#apidoc.element.express.application.purge)
- description and source-code
```javascript
purge = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.put"></a>[function <span class="apidocSignatureSpan">express.application.</span>put (path)](#apidoc.element.express.application.put)
- description and source-code
```javascript
put = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.rebind"></a>[function <span class="apidocSignatureSpan">express.application.</span>rebind (path)](#apidoc.element.express.application.rebind)
- description and source-code
```javascript
rebind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.render"></a>[function <span class="apidocSignatureSpan">express.application.</span>render (name, options, callback)](#apidoc.element.express.application.render)
- description and source-code
```javascript
function render(name, options, callback) {
  var cache = this.cache;
  var done = callback;
  var engines = this.engines;
  var opts = options;
  var renderOptions = {};
  var view;

  // support callback function as second arg
  if (typeof options === 'function') {
    done = options;
    opts = {};
  }

  // merge app.locals
  merge(renderOptions, this.locals);

  // merge options._locals
  if (opts._locals) {
    merge(renderOptions, opts._locals);
  }

  // merge options
  merge(renderOptions, opts);

  // set .cache unless explicitly provided
  if (renderOptions.cache == null) {
    renderOptions.cache = this.enabled('view cache');
  }

  // primed cache
  if (renderOptions.cache) {
    view = cache[name];
  }

  // view
  if (!view) {
    var View = this.get('view');

    view = new View(name, {
      defaultEngine: this.get('view engine'),
      root: this.get('views'),
      engines: engines
    });

    if (!view.path) {
      var dirs = Array.isArray(view.root) && view.root.length > 1
        ? 'directories "' + view.root.slice(0, -1).join('", "') + '" or "' + view.root[view.root.length - 1] + '"'
        : 'directory "' + view.root + '"'
      var err = new Error('Failed to lookup view "' + name + '" in views ' + dirs);
      err.view = view;
      return done(err);
    }

    // prime the cache
    if (renderOptions.cache) {
      cache[name] = view;
    }
  }

  // render
  tryRender(view, renderOptions, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.report"></a>[function <span class="apidocSignatureSpan">express.application.</span>report (path)](#apidoc.element.express.application.report)
- description and source-code
```javascript
report = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.route"></a>[function <span class="apidocSignatureSpan">express.application.</span>route (path)](#apidoc.element.express.application.route)
- description and source-code
```javascript
function route(path) {
  this.lazyrouter();
  return this._router.route(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.search"></a>[function <span class="apidocSignatureSpan">express.application.</span>search (path)](#apidoc.element.express.application.search)
- description and source-code
```javascript
search = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.set"></a>[function <span class="apidocSignatureSpan">express.application.</span>set (setting, val)](#apidoc.element.express.application.set)
- description and source-code
```javascript
function set(setting, val) {
  if (arguments.length === 1) {
    // app.get(setting)
    return this.settings[setting];
  }

  debug('set "%s" to %o', setting, val);

  // set value
  this.settings[setting] = val;

  // trigger matched settings
  switch (setting) {
    case 'etag':
      this.set('etag fn', compileETag(val));
      break;
    case 'query parser':
      this.set('query parser fn', compileQueryParser(val));
      break;
    case 'trust proxy':
      this.set('trust proxy fn', compileTrust(val));

      // trust proxy inherit back-compat
      Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
        configurable: true,
        value: false
      });

      break;
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.subscribe"></a>[function <span class="apidocSignatureSpan">express.application.</span>subscribe (path)](#apidoc.element.express.application.subscribe)
- description and source-code
```javascript
subscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.trace"></a>[function <span class="apidocSignatureSpan">express.application.</span>trace (path)](#apidoc.element.express.application.trace)
- description and source-code
```javascript
trace = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.unbind"></a>[function <span class="apidocSignatureSpan">express.application.</span>unbind (path)](#apidoc.element.express.application.unbind)
- description and source-code
```javascript
unbind = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.unlink"></a>[function <span class="apidocSignatureSpan">express.application.</span>unlink (path)](#apidoc.element.express.application.unlink)
- description and source-code
```javascript
unlink = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.unlock"></a>[function <span class="apidocSignatureSpan">express.application.</span>unlock (path)](#apidoc.element.express.application.unlock)
- description and source-code
```javascript
unlock = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.unsubscribe"></a>[function <span class="apidocSignatureSpan">express.application.</span>unsubscribe (path)](#apidoc.element.express.application.unsubscribe)
- description and source-code
```javascript
unsubscribe = function (path){
  if (method === 'get' && arguments.length === 1) {
    // app.get(setting)
    return this.set(path);
  }

  this.lazyrouter();

  var route = this._router.route(path);
  route[method].apply(route, slice.call(arguments, 1));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.application.use"></a>[function <span class="apidocSignatureSpan">express.application.</span>use (fn)](#apidoc.element.express.application.use)
- description and source-code
```javascript
function use(fn) {
  var offset = 0;
  var path = '/';

  // default path to '/'
  // disambiguate app.use([fn])
  if (typeof fn !== 'function') {
    var arg = fn;

    while (Array.isArray(arg) && arg.length !== 0) {
      arg = arg[0];
    }

    // first arg is the path
    if (typeof arg !== 'function') {
      offset = 1;
      path = fn;
    }
  }

  var fns = flatten(slice.call(arguments, offset));

  if (fns.length === 0) {
    throw new TypeError('app.use() requires middleware functions');
  }

  // setup router
  this.lazyrouter();
  var router = this._router;

  fns.forEach(function (fn) {
    // non-express app
    if (!fn || !fn.handle || !fn.set) {
      return router.use(path, fn);
    }

    debug('.use app under %s', path);
    fn.mountpath = path;
    fn.parent = this;

    // restore .app property on req and res
    router.use(path, function mounted_app(req, res, next) {
      var orig = req.app;
      fn.handle(req, res, function (err) {
        setPrototyeOf(req, orig.request)
        setPrototyeOf(res, orig.response)
        next(err);
      });
    });

    // mounted an app
    fn.emit('mount', this);
  }, this);

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.request"></a>[module express.request](#apidoc.module.express.request)

#### <a name="apidoc.element.express.request.accepts"></a>[function <span class="apidocSignatureSpan">express.request.</span>accepts ()](#apidoc.element.express.request.accepts)
- description and source-code
```javascript
accepts = function (){
  var accept = accepts(this);
  return accept.types.apply(accept, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.acceptsCharset"></a>[function <span class="apidocSignatureSpan">express.request.</span>acceptsCharset ()](#apidoc.element.express.request.acceptsCharset)
- description and source-code
```javascript
acceptsCharset = function () {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.acceptsCharsets"></a>[function <span class="apidocSignatureSpan">express.request.</span>acceptsCharsets ()](#apidoc.element.express.request.acceptsCharsets)
- description and source-code
```javascript
acceptsCharsets = function (){
  var accept = accepts(this);
  return accept.charsets.apply(accept, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.acceptsEncoding"></a>[function <span class="apidocSignatureSpan">express.request.</span>acceptsEncoding ()](#apidoc.element.express.request.acceptsEncoding)
- description and source-code
```javascript
acceptsEncoding = function () {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.acceptsEncodings"></a>[function <span class="apidocSignatureSpan">express.request.</span>acceptsEncodings ()](#apidoc.element.express.request.acceptsEncodings)
- description and source-code
```javascript
acceptsEncodings = function (){
  var accept = accepts(this);
  return accept.encodings.apply(accept, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.acceptsLanguage"></a>[function <span class="apidocSignatureSpan">express.request.</span>acceptsLanguage ()](#apidoc.element.express.request.acceptsLanguage)
- description and source-code
```javascript
acceptsLanguage = function () {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.acceptsLanguages"></a>[function <span class="apidocSignatureSpan">express.request.</span>acceptsLanguages ()](#apidoc.element.express.request.acceptsLanguages)
- description and source-code
```javascript
acceptsLanguages = function (){
  var accept = accepts(this);
  return accept.languages.apply(accept, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.get"></a>[function <span class="apidocSignatureSpan">express.request.</span>get (name)](#apidoc.element.express.request.get)
- description and source-code
```javascript
function header(name) {
  if (!name) {
    throw new TypeError('name argument is required to req.get');
  }

  if (typeof name !== 'string') {
    throw new TypeError('name must be a string to req.get');
  }

  var lc = name.toLowerCase();

  switch (lc) {
    case 'referer':
    case 'referrer':
      return this.headers.referrer
        || this.headers.referer;
    default:
      return this.headers[lc];
  }
}
```
- example usage
```shell
...
  [![Windows Build][appveyor-image]][appveyor-url]
  [![Test Coverage][coveralls-image]][coveralls-url]

'''js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
'''

## Installation
...
```

#### <a name="apidoc.element.express.request.header"></a>[function <span class="apidocSignatureSpan">express.request.</span>header (name)](#apidoc.element.express.request.header)
- description and source-code
```javascript
function header(name) {
  if (!name) {
    throw new TypeError('name argument is required to req.get');
  }

  if (typeof name !== 'string') {
    throw new TypeError('name must be a string to req.get');
  }

  var lc = name.toLowerCase();

  switch (lc) {
    case 'referer':
    case 'referrer':
      return this.headers.referrer
        || this.headers.referer;
    default:
      return this.headers[lc];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.is"></a>[function <span class="apidocSignatureSpan">express.request.</span>is (types)](#apidoc.element.express.request.is)
- description and source-code
```javascript
function is(types) {
  var arr = types;

  // support flattened arguments
  if (!Array.isArray(types)) {
    arr = new Array(arguments.length);
    for (var i = 0; i < arr.length; i++) {
      arr[i] = arguments[i];
    }
  }

  return typeis(this, arr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.param"></a>[function <span class="apidocSignatureSpan">express.request.</span>param (name, defaultValue)](#apidoc.element.express.request.param)
- description and source-code
```javascript
function param(name, defaultValue) {
  var params = this.params || {};
  var body = this.body || {};
  var query = this.query || {};

  var args = arguments.length === 1
    ? 'name'
    : 'name, default';
  deprecate('req.param(' + args + '): Use req.params, req.body, or req.query instead');

  if (null != params[name] && params.hasOwnProperty(name)) return params[name];
  if (null != body[name]) return body[name];
  if (null != query[name]) return query[name];

  return defaultValue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.request.range"></a>[function <span class="apidocSignatureSpan">express.request.</span>range (size, options)](#apidoc.element.express.request.range)
- description and source-code
```javascript
function range(size, options) {
  var range = this.get('Range');
  if (!range) return;
  return parseRange(size, range, options);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.response"></a>[module express.response](#apidoc.module.express.response)

#### <a name="apidoc.element.express.response.append"></a>[function <span class="apidocSignatureSpan">express.response.</span>append (field, val)](#apidoc.element.express.response.append)
- description and source-code
```javascript
function append(field, val) {
  var prev = this.get(field);
  var value = val;

  if (prev) {
    // concat the new and prev vals
    value = Array.isArray(prev) ? prev.concat(val)
      : Array.isArray(val) ? [prev].concat(val)
      : [prev, val];
  }

  return this.set(field, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.attachment"></a>[function <span class="apidocSignatureSpan">express.response.</span>attachment (filename)](#apidoc.element.express.response.attachment)
- description and source-code
```javascript
function attachment(filename) {
  if (filename) {
    this.type(extname(filename));
  }

  this.set('Content-Disposition', contentDisposition(filename));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.clearCookie"></a>[function <span class="apidocSignatureSpan">express.response.</span>clearCookie (name, options)](#apidoc.element.express.response.clearCookie)
- description and source-code
```javascript
function clearCookie(name, options) {
  var opts = merge({ expires: new Date(1), path: '/' }, options);

  return this.cookie(name, '', opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.contentType"></a>[function <span class="apidocSignatureSpan">express.response.</span>contentType (type)](#apidoc.element.express.response.contentType)
- description and source-code
```javascript
function contentType(type) {
  var ct = type.indexOf('/') === -1
    ? mime.lookup(type)
    : type;

  return this.set('Content-Type', ct);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.cookie"></a>[function <span class="apidocSignatureSpan">express.response.</span>cookie (name, value, options)](#apidoc.element.express.response.cookie)
- description and source-code
```javascript
cookie = function (name, value, options) {
  var opts = merge({}, options);
  var secret = this.req.secret;
  var signed = opts.signed;

  if (signed && !secret) {
    throw new Error('cookieParser("secret") required for signed cookies');
  }

  var val = typeof value === 'object'
    ? 'j:' + JSON.stringify(value)
    : String(value);

  if (signed) {
    val = 's:' + sign(val, secret);
  }

  if ('maxAge' in opts) {
    opts.expires = new Date(Date.now() + opts.maxAge);
    opts.maxAge /= 1000;
  }

  if (opts.path == null) {
    opts.path = '/';
  }

  this.append('Set-Cookie', cookie.serialize(name, String(val), opts));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.download"></a>[function <span class="apidocSignatureSpan">express.response.</span>download (path, filename, callback)](#apidoc.element.express.response.download)
- description and source-code
```javascript
function download(path, filename, callback) {
  var done = callback;
  var name = filename;

  // support function as second arg
  if (typeof filename === 'function') {
    done = filename;
    name = null;
  }

  // set Content-Disposition when file is sent
  var headers = {
    'Content-Disposition': contentDisposition(name || path)
  };

  // Resolve the full path for sendFile
  var fullPath = resolve(path);

  return this.sendFile(fullPath, { headers: headers }, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.format"></a>[function <span class="apidocSignatureSpan">express.response.</span>format (obj)](#apidoc.element.express.response.format)
- description and source-code
```javascript
format = function (obj){
  var req = this.req;
  var next = req.next;

  var fn = obj.default;
  if (fn) delete obj.default;
  var keys = Object.keys(obj);

  var key = keys.length > 0
    ? req.accepts(keys)
    : false;

  this.vary("Accept");

  if (key) {
    this.set('Content-Type', normalizeType(key).value);
    obj[key](req, this, next);
  } else if (fn) {
    fn();
  } else {
    var err = new Error('Not Acceptable');
    err.status = err.statusCode = 406;
    err.types = normalizeTypes(keys).map(function(o){ return o.value });
    next(err);
  }

  return this;
}
```
- example usage
```shell
...
 // parse type
 var parsed = contentType.parse(type);

 // set charset
 parsed.parameters.charset = charset;

 // format type
 return contentType.format(parsed);
};

/**
* Parse an extended query string with qs.
*
* @return {Object}
* @private
...
```

#### <a name="apidoc.element.express.response.get"></a>[function <span class="apidocSignatureSpan">express.response.</span>get (field)](#apidoc.element.express.response.get)
- description and source-code
```javascript
get = function (field){
  return this.getHeader(field);
}
```
- example usage
```shell
...
  [![Windows Build][appveyor-image]][appveyor-url]
  [![Test Coverage][coveralls-image]][coveralls-url]

'''js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
'''

## Installation
...
```

#### <a name="apidoc.element.express.response.header"></a>[function <span class="apidocSignatureSpan">express.response.</span>header (field, val)](#apidoc.element.express.response.header)
- description and source-code
```javascript
function header(field, val) {
  if (arguments.length === 2) {
    var value = Array.isArray(val)
      ? val.map(String)
      : String(val);

    // add charset to content-type
    if (field.toLowerCase() === 'content-type' && !charsetRegExp.test(value)) {
      var charset = mime.charsets.lookup(value.split(';')[0]);
      if (charset) value += '; charset=' + charset.toLowerCase();
    }

    this.setHeader(field, value);
  } else {
    for (var key in field) {
      this.set(key, field[key]);
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.json"></a>[function <span class="apidocSignatureSpan">express.response.</span>json (obj)](#apidoc.element.express.response.json)
- description and source-code
```javascript
function json(obj) {
  var val = obj;

  // allow status / body
  if (arguments.length === 2) {
    // res.json(body, status) backwards compat
    if (typeof arguments[1] === 'number') {
      deprecate('res.json(obj, status): Use res.status(status).json(obj) instead');
      this.statusCode = arguments[1];
    } else {
      deprecate('res.json(status, obj): Use res.status(status).json(obj) instead');
      this.statusCode = arguments[0];
      val = arguments[1];
    }
  }

  // settings
  var app = this.app;
  var replacer = app.get('json replacer');
  var spaces = app.get('json spaces');
  var body = stringify(val, replacer, spaces);

  // content-type
  if (!this.get('Content-Type')) {
    this.set('Content-Type', 'application/json');
  }

  return this.send(body);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.jsonp"></a>[function <span class="apidocSignatureSpan">express.response.</span>jsonp (obj)](#apidoc.element.express.response.jsonp)
- description and source-code
```javascript
function jsonp(obj) {
  var val = obj;

  // allow status / body
  if (arguments.length === 2) {
    // res.json(body, status) backwards compat
    if (typeof arguments[1] === 'number') {
      deprecate('res.jsonp(obj, status): Use res.status(status).json(obj) instead');
      this.statusCode = arguments[1];
    } else {
      deprecate('res.jsonp(status, obj): Use res.status(status).jsonp(obj) instead');
      this.statusCode = arguments[0];
      val = arguments[1];
    }
  }

  // settings
  var app = this.app;
  var replacer = app.get('json replacer');
  var spaces = app.get('json spaces');
  var body = stringify(val, replacer, spaces);
  var callback = this.req.query[app.get('jsonp callback name')];

  // content-type
  if (!this.get('Content-Type')) {
    this.set('X-Content-Type-Options', 'nosniff');
    this.set('Content-Type', 'application/json');
  }

  // fixup callback
  if (Array.isArray(callback)) {
    callback = callback[0];
  }

  // jsonp
  if (typeof callback === 'string' && callback.length !== 0) {
    this.charset = 'utf-8';
    this.set('X-Content-Type-Options', 'nosniff');
    this.set('Content-Type', 'text/javascript');

    // restrict callback charset
    callback = callback.replace(/[^\[\]\w$.]/g, '');

    // replace chars not allowed in JavaScript that are in JSON
    body = body
      .replace(/\u2028/g, '\\u2028')
      .replace(/\u2029/g, '\\u2029');

    // the /**/ is a specific security mitigation for "Rosetta Flash JSONP abuse"
    // the typeof check is just to reduce client error noise
    body = '/**/ typeof ' + callback + ' === \'function\' && ' + callback + '(' + body + ');';
  }

  return this.send(body);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.links"></a>[function <span class="apidocSignatureSpan">express.response.</span>links (links)](#apidoc.element.express.response.links)
- description and source-code
```javascript
links = function (links){
  var link = this.get('Link') || '';
  if (link) link += ', ';
  return this.set('Link', link + Object.keys(links).map(function(rel){
    return '<' + links[rel] + '>; rel="' + rel + '"';
  }).join(', '));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.location"></a>[function <span class="apidocSignatureSpan">express.response.</span>location (url)](#apidoc.element.express.response.location)
- description and source-code
```javascript
function location(url) {
  var loc = url;

  // "back" is an alias for the referrer
  if (url === 'back') {
    loc = this.req.get('Referrer') || '/';
  }

  // set location
  return this.set('Location', encodeUrl(loc));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.redirect"></a>[function <span class="apidocSignatureSpan">express.response.</span>redirect (url)](#apidoc.element.express.response.redirect)
- description and source-code
```javascript
function redirect(url) {
  var address = url;
  var body;
  var status = 302;

  // allow status / url
  if (arguments.length === 2) {
    if (typeof arguments[0] === 'number') {
      status = arguments[0];
      address = arguments[1];
    } else {
      deprecate('res.redirect(url, status): Use res.redirect(status, url) instead');
      status = arguments[1];
    }
  }

  // Set location header
  address = this.location(address).get('Location');

  // Support text/{plain,html} by default
  this.format({
    text: function(){
      body = statuses[status] + '. Redirecting to ' + address
    },

    html: function(){
      var u = escapeHtml(address);
      body = '<p>' + statuses[status] + '. Redirecting to <a href="' + u + '">' + u + '</a></p>'
    },

    default: function(){
      body = '';
    }
  });

  // Respond
  this.statusCode = status;
  this.set('Content-Length', Buffer.byteLength(body));

  if (this.req.method === 'HEAD') {
    this.end();
  } else {
    this.end(body);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.render"></a>[function <span class="apidocSignatureSpan">express.response.</span>render (view, options, callback)](#apidoc.element.express.response.render)
- description and source-code
```javascript
function render(view, options, callback) {
  var app = this.req.app;
  var done = callback;
  var opts = options || {};
  var req = this.req;
  var self = this;

  // support callback function as second arg
  if (typeof options === 'function') {
    done = options;
    opts = {};
  }

  // merge res.locals
  opts._locals = self.locals;

  // default callback to respond
  done = done || function (err, str) {
    if (err) return req.next(err);
    self.send(str);
  };

  // render
  app.render(view, opts, done);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.send"></a>[function <span class="apidocSignatureSpan">express.response.</span>send (body)](#apidoc.element.express.response.send)
- description and source-code
```javascript
function send(body) {
  var chunk = body;
  var encoding;
  var len;
  var req = this.req;
  var type;

  // settings
  var app = this.app;

  // allow status / body
  if (arguments.length === 2) {
    // res.send(body, status) backwards compat
    if (typeof arguments[0] !== 'number' && typeof arguments[1] === 'number') {
      deprecate('res.send(body, status): Use res.status(status).send(body) instead');
      this.statusCode = arguments[1];
    } else {
      deprecate('res.send(status, body): Use res.status(status).send(body) instead');
      this.statusCode = arguments[0];
      chunk = arguments[1];
    }
  }

  // disambiguate res.send(status) and res.send(status, num)
  if (typeof chunk === 'number' && arguments.length === 1) {
    // res.send(status) will set status message as text string
    if (!this.get('Content-Type')) {
      this.type('txt');
    }

    deprecate('res.send(status): Use res.sendStatus(status) instead');
    this.statusCode = chunk;
    chunk = statuses[chunk]
  }

  switch (typeof chunk) {
    // string defaulting to html
    case 'string':
      if (!this.get('Content-Type')) {
        this.type('html');
      }
      break;
    case 'boolean':
    case 'number':
    case 'object':
      if (chunk === null) {
        chunk = '';
      } else if (Buffer.isBuffer(chunk)) {
        if (!this.get('Content-Type')) {
          this.type('bin');
        }
      } else {
        return this.json(chunk);
      }
      break;
  }

  // write strings in utf-8
  if (typeof chunk === 'string') {
    encoding = 'utf8';
    type = this.get('Content-Type');

    // reflect this in content-type
    if (typeof type === 'string') {
      this.set('Content-Type', setCharset(type, 'utf-8'));
    }
  }

  // populate Content-Length
  if (chunk !== undefined) {
    if (!Buffer.isBuffer(chunk)) {
      // convert chunk to Buffer; saves later double conversions
      chunk = new Buffer(chunk, encoding);
      encoding = undefined;
    }

    len = chunk.length;
    this.set('Content-Length', len);
  }

  // populate ETag
  var etag;
  var generateETag = len !== undefined && app.get('etag fn');
  if (typeof generateETag === 'function' && !this.get('ETag')) {
    if ((etag = generateETag(chunk, encoding))) {
      this.set('ETag', etag);
    }
  }

  // freshness
  if (req.fresh) this.statusCode = 304;

  // strip irrelevant headers
  if (204 === this.statusCode || 304 === this.statusCode) {
    this.removeHeader('Content-Type');
    this.removeHeader('Content-Length');
    this.removeHeader('Transfer-Encoding');
    chunk = '';
  }

  if (req.method === 'HEAD') {
    // skip body for HEAD
    this.end();
  } else {
    // respond
    this.end(chunk, encoding);
  }

  return this;
}
```
- example usage
```shell
...
  [![Test Coverage][coveralls-image]][coveralls-url]

'''js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
'''

## Installation
...
```

#### <a name="apidoc.element.express.response.sendFile"></a>[function <span class="apidocSignatureSpan">express.response.</span>sendFile (path, options, callback)](#apidoc.element.express.response.sendFile)
- description and source-code
```javascript
function sendFile(path, options, callback) {
  var done = callback;
  var req = this.req;
  var res = this;
  var next = req.next;
  var opts = options || {};

  if (!path) {
    throw new TypeError('path argument is required to res.sendFile');
  }

  // support function as second arg
  if (typeof options === 'function') {
    done = options;
    opts = {};
  }

  if (!opts.root && !isAbsolute(path)) {
    throw new TypeError('path must be absolute or specify root to res.sendFile');
  }

  // create file stream
  var pathname = encodeURI(path);
  var file = send(req, pathname, opts);

  // transfer
  sendfile(res, file, opts, function (err) {
    if (done) return done(err);
    if (err && err.code === 'EISDIR') return next();

    // next() all but write errors
    if (err && err.code !== 'ECONNABORTED' && err.syscall !== 'write') {
      next(err);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.sendStatus"></a>[function <span class="apidocSignatureSpan">express.response.</span>sendStatus (statusCode)](#apidoc.element.express.response.sendStatus)
- description and source-code
```javascript
function sendStatus(statusCode) {
  var body = statuses[statusCode] || String(statusCode)

  this.statusCode = statusCode;
  this.type('txt');

  return this.send(body);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.sendfile"></a>[function <span class="apidocSignatureSpan">express.response.</span>sendfile (arg0, arg1, arg2)](#apidoc.element.express.response.sendfile)
- description and source-code
```javascript
sendfile = function (arg0, arg1, arg2) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.set"></a>[function <span class="apidocSignatureSpan">express.response.</span>set (field, val)](#apidoc.element.express.response.set)
- description and source-code
```javascript
function header(field, val) {
  if (arguments.length === 2) {
    var value = Array.isArray(val)
      ? val.map(String)
      : String(val);

    // add charset to content-type
    if (field.toLowerCase() === 'content-type' && !charsetRegExp.test(value)) {
      var charset = mime.charsets.lookup(value.split(';')[0]);
      if (charset) value += '; charset=' + charset.toLowerCase();
    }

    this.setHeader(field, value);
  } else {
    for (var key in field) {
      this.set(key, field[key]);
    }
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.status"></a>[function <span class="apidocSignatureSpan">express.response.</span>status (code)](#apidoc.element.express.response.status)
- description and source-code
```javascript
function status(code) {
  this.statusCode = code;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.type"></a>[function <span class="apidocSignatureSpan">express.response.</span>type (type)](#apidoc.element.express.response.type)
- description and source-code
```javascript
function contentType(type) {
  var ct = type.indexOf('/') === -1
    ? mime.lookup(type)
    : type;

  return this.set('Content-Type', ct);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.response.vary"></a>[function <span class="apidocSignatureSpan">express.response.</span>vary (field)](#apidoc.element.express.response.vary)
- description and source-code
```javascript
vary = function (field){
  // checks for back-compat
  if (!field || (Array.isArray(field) && !field.length)) {
    deprecate('res.vary(): Provide a field name');
    return this;
  }

  vary(this, field);

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.utils"></a>[module express.utils](#apidoc.module.express.utils)

#### <a name="apidoc.element.express.utils.compileETag"></a>[function <span class="apidocSignatureSpan">express.utils.</span>compileETag (val)](#apidoc.element.express.utils.compileETag)
- description and source-code
```javascript
compileETag = function (val) {
  var fn;

  if (typeof val === 'function') {
    return val;
  }

  switch (val) {
    case true:
      fn = exports.wetag;
      break;
    case false:
      break;
    case 'strong':
      fn = exports.etag;
      break;
    case 'weak':
      fn = exports.wetag;
      break;
    default:
      throw new TypeError('unknown value for etag function: ' + val);
  }

  return fn;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.compileQueryParser"></a>[function <span class="apidocSignatureSpan">express.utils.</span>compileQueryParser (val)](#apidoc.element.express.utils.compileQueryParser)
- description and source-code
```javascript
function compileQueryParser(val) {
  var fn;

  if (typeof val === 'function') {
    return val;
  }

  switch (val) {
    case true:
      fn = querystring.parse;
      break;
    case false:
      fn = newObject;
      break;
    case 'extended':
      fn = parseExtendedQueryString;
      break;
    case 'simple':
      fn = querystring.parse;
      break;
    default:
      throw new TypeError('unknown value for query parser function: ' + val);
  }

  return fn;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.compileTrust"></a>[function <span class="apidocSignatureSpan">express.utils.</span>compileTrust (val)](#apidoc.element.express.utils.compileTrust)
- description and source-code
```javascript
compileTrust = function (val) {
  if (typeof val === 'function') return val;

  if (val === true) {
    // Support plain true/false
    return function(){ return true };
  }

  if (typeof val === 'number') {
    // Support trusting hop count
    return function(a, i){ return i < val };
  }

  if (typeof val === 'string') {
    // Support comma-separated values
    val = val.split(/ *, */);
  }

  return proxyaddr.compile(val || []);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.contentDisposition"></a>[function <span class="apidocSignatureSpan">express.utils.</span>contentDisposition (arg0, arg1)](#apidoc.element.express.utils.contentDisposition)
- description and source-code
```javascript
contentDisposition = function (arg0, arg1) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.etag"></a>[function <span class="apidocSignatureSpan">express.utils.</span>etag (body, encoding)](#apidoc.element.express.utils.etag)
- description and source-code
```javascript
etag = function (body, encoding) {
  var buf = !Buffer.isBuffer(body)
    ? new Buffer(body, encoding)
    : body;

  return etag(buf, {weak: false});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.flatten"></a>[function <span class="apidocSignatureSpan">express.utils.</span>flatten (arg0, arg1)](#apidoc.element.express.utils.flatten)
- description and source-code
```javascript
flatten = function (arg0, arg1) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.isAbsolute"></a>[function <span class="apidocSignatureSpan">express.utils.</span>isAbsolute (path)](#apidoc.element.express.utils.isAbsolute)
- description and source-code
```javascript
isAbsolute = function (path){
  if ('/' === path[0]) return true;
  if (':' === path[1] && ('\\' === path[2] || '/' === path[2])) return true; // Windows device path
  if ('\\\\' === path.substring(0, 2)) return true; // Microsoft Azure absolute path
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.normalizeType"></a>[function <span class="apidocSignatureSpan">express.utils.</span>normalizeType (type)](#apidoc.element.express.utils.normalizeType)
- description and source-code
```javascript
normalizeType = function (type){
  return ~type.indexOf('/')
    ? acceptParams(type)
    : { value: mime.lookup(type), params: {} };
}
```
- example usage
```shell
...
* @api private
*/

exports.normalizeTypes = function(types){
 var ret = [];

 for (var i = 0; i < types.length; ++i) {
   ret.push(exports.normalizeType(types[i]));
 }

 return ret;
};

/**
* Generate Content-Disposition header appropriate for the filename.
...
```

#### <a name="apidoc.element.express.utils.normalizeTypes"></a>[function <span class="apidocSignatureSpan">express.utils.</span>normalizeTypes (types)](#apidoc.element.express.utils.normalizeTypes)
- description and source-code
```javascript
normalizeTypes = function (types){
  var ret = [];

  for (var i = 0; i < types.length; ++i) {
    ret.push(exports.normalizeType(types[i]));
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.setCharset"></a>[function <span class="apidocSignatureSpan">express.utils.</span>setCharset (type, charset)](#apidoc.element.express.utils.setCharset)
- description and source-code
```javascript
function setCharset(type, charset) {
  if (!type || !charset) {
    return type;
  }

  // parse type
  var parsed = contentType.parse(type);

  // set charset
  parsed.parameters.charset = charset;

  // format type
  return contentType.format(parsed);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.utils.wetag"></a>[function <span class="apidocSignatureSpan">express.utils.</span>wetag (body, encoding)](#apidoc.element.express.utils.wetag)
- description and source-code
```javascript
function wetag(body, encoding){
  var buf = !Buffer.isBuffer(body)
    ? new Buffer(body, encoding)
    : body;

  return etag(buf, {weak: true});
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.view"></a>[module express.view](#apidoc.module.express.view)

#### <a name="apidoc.element.express.view.view"></a>[function <span class="apidocSignatureSpan">express.</span>view (name, options)](#apidoc.element.express.view.view)
- description and source-code
```javascript
function View(name, options) {
  var opts = options || {};

  this.defaultEngine = opts.defaultEngine;
  this.ext = extname(name);
  this.name = name;
  this.root = opts.root;

  if (!this.ext && !this.defaultEngine) {
    throw new Error('No default engine was specified and no extension was provided.');
  }

  var fileName = name;

  if (!this.ext) {
    // get extension from default engine name
    this.ext = this.defaultEngine[0] !== '.'
      ? '.' + this.defaultEngine
      : this.defaultEngine;

    fileName += this.ext;
  }

  if (!opts.engines[this.ext]) {
    // load engine
    var mod = this.ext.substr(1)
    debug('require "%s"', mod)
    opts.engines[this.ext] = require(mod).__express
  }

  // store loaded engine
  this.engine = opts.engines[this.ext];

  // lookup path
  this.path = this.lookup(fileName);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.express.view.prototype"></a>[module express.view.prototype](#apidoc.module.express.view.prototype)

#### <a name="apidoc.element.express.view.prototype.lookup"></a>[function <span class="apidocSignatureSpan">express.view.prototype.</span>lookup (name)](#apidoc.element.express.view.prototype.lookup)
- description and source-code
```javascript
function lookup(name) {
  var path;
  var roots = [].concat(this.root);

  debug('lookup "%s"', name);

  for (var i = 0; i < roots.length && !path; i++) {
    var root = roots[i];

    // resolve the path
    var loc = resolve(root, name);
    var dir = dirname(loc);
    var file = basename(loc);

    // resolve the file
    path = this.resolve(dir, file);
  }

  return path;
}
```
- example usage
```shell
...
* @return {Object}
* @api private
*/

exports.normalizeType = function(type){
 return ~type.indexOf('/')
   ? acceptParams(type)
   : { value: mime.lookup(type), params: {} };
};

/**
* Normalize 'types', for example "html" becomes "text/html".
*
* @param {Array} types
* @return {Array}
...
```

#### <a name="apidoc.element.express.view.prototype.render"></a>[function <span class="apidocSignatureSpan">express.view.prototype.</span>render (options, callback)](#apidoc.element.express.view.prototype.render)
- description and source-code
```javascript
function render(options, callback) {
  debug('render "%s"', this.path);
  this.engine(this.path, options, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.express.view.prototype.resolve"></a>[function <span class="apidocSignatureSpan">express.view.prototype.</span>resolve (dir, file)](#apidoc.element.express.view.prototype.resolve)
- description and source-code
```javascript
function resolve(dir, file) {
  var ext = this.ext;

  // <path>.<ext>
  var path = join(dir, file);
  var stat = tryStat(path);

  if (stat && stat.isFile()) {
    return path;
  }

  // <path>/index.<ext>
  path = join(dir, basename(file, ext), 'index' + ext);
  stat = tryStat(path);

  if (stat && stat.isFile()) {
    return path;
  }
}
```
- example usage
```shell
...

   // resolve the path
   var loc = resolve(root, name);
   var dir = dirname(loc);
   var file = basename(loc);

   // resolve the file
   path = this.resolve(dir, file);
 }

 return path;
};

/**
* Render with the given options.
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
