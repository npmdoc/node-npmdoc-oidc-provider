# npmdoc-oidc-provider

#### basic api documentation for  [oidc-provider (v1.15.6)](https://github.com/panva/node-oidc-provider)  [![npm package](https://img.shields.io/npm/v/npmdoc-oidc-provider.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-oidc-provider) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-oidc-provider.svg)](https://travis-ci.org/npmdoc/node-npmdoc-oidc-provider)

#### OpenID Provider (OP) implementation for Node.js OpenID Connect servers.

[![NPM](https://nodei.co/npm/oidc-provider.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/oidc-provider)

- [https://npmdoc.github.io/node-npmdoc-oidc-provider/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-oidc-provider/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-oidc-provider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-oidc-provider/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-oidc-provider/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-oidc-provider/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Filip Skokan"
    },
    "bugs": {
        "url": "https://github.com/panva/node-oidc-provider/issues"
    },
    "dependencies": {
        "base64url": "^2.0.0",
        "buffer-equals-constant": "^1.0.0",
        "debug": "^2.4.4",
        "ejs": "^2.5.2",
        "got": "^6.1.1",
        "http-errors": "^1.4.0",
        "kcors": "^1.2.1",
        "koa": "^1.0.0",
        "koa-compose": "^2.3.0",
        "koa-router": "^5.2.3",
        "lodash": "^4.5.0",
        "lru-cache": "^4.0.0",
        "node-jose": "^0.9.4",
        "oidc-token-hash": "^1.0.0",
        "raw-body": "^2.1.7",
        "uuid": "^3.0.0",
        "valid-url": "^1.0.9"
    },
    "description": "OpenID Provider (OP) implementation for Node.js OpenID Connect servers.",
    "devDependencies": {
        "chai": "^3.5.0",
        "co-mocha": "^1.1.2",
        "eslint": "^3.0.0",
        "eslint-config-airbnb-base": "^11.0.0",
        "eslint-plugin-import": "^2.0.1",
        "istanbul": "~0.4.3",
        "koa-body": "^1.2.1",
        "koa-ejs": "^3.0.0",
        "koa-mount": "^1.3.0",
        "koa-rewrite": "^1.1.1",
        "mocha": "^3.0.0",
        "moment": "^2.14.1",
        "nock": "^9.0.2",
        "sinon": "^2.1.0",
        "supertest": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "be3ea3acd43c23b5f8e9267a90e74dd860521a06",
        "tarball": "https://registry.npmjs.org/oidc-provider/-/oidc-provider-1.15.6.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "lib"
    ],
    "gitHead": "9d55c7a34761e6c5fc8552a755804fca29894cbc",
    "homepage": "https://github.com/panva/node-oidc-provider",
    "keywords": [
        "openid",
        "connect",
        "provider",
        "certified",
        "server",
        "dynamic",
        "config",
        "basic",
        "hybrid",
        "implicit",
        "oidc",
        "auth",
        "authentication",
        "identity",
        "oauth",
        "oauth2",
        "express",
        "koa"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "panva"
        }
    ],
    "name": "oidc-provider",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/panva/node-oidc-provider.git"
    },
    "scripts": {
        "coverage": "make coverage",
        "heroku-postbuild": "npm install mongodb",
        "lint": "eslint lib example test",
        "lint-fix": "eslint lib example test --fix",
        "test": "make test"
    },
    "version": "1.15.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
