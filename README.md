# npmtest-ember-cli-simple-auth-token

#### basic test coverage for  [ember-cli-simple-auth-token (v0.7.3)](https://github.com/jpadilla/ember-cli-simple-auth-token#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-simple-auth-token.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-simple-auth-token) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-simple-auth-token.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-simple-auth-token)

#### An authenticator and authorizer for Ember Simple Auth that is compatible with token-based authentication like JWT in Ember CLI applications.

[![NPM](https://nodei.co/npm/ember-cli-simple-auth-token.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-simple-auth-token)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-simple-auth-token/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-simple-auth-token/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-simple-auth-token/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-simple-auth-token/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-simple-auth-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-simple-auth-token/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-simple-auth-token/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "José Padilla",
        "url": "http://jpadilla.com"
    },
    "bugs": {
        "url": "https://github.com/jpadilla/ember-cli-simple-auth-token/issues"
    },
    "contributors": [
        {
            "name": "Giovanni Collazo"
        }
    ],
    "dependencies": {
        "ember-cli-babel": "^5.0.0"
    },
    "deprecated": "1.0.0 was released under ember-simple-auth-token",
    "description": "An authenticator and authorizer for Ember Simple Auth that is compatible with token-based authentication like JWT in Ember CLI applications.",
    "devDependencies": {
        "body-parser": "^1.12.4",
        "broccoli-asset-rev": "^2.0.2",
        "broccoli-funnel": "^0.2.3",
        "ember-cli": "1.13.1",
        "ember-cli-app-version": "0.4.0",
        "ember-cli-content-security-policy": "0.4.0",
        "ember-cli-dependency-checker": "^1.0.0",
        "ember-cli-github-pages": "0.0.4",
        "ember-cli-htmlbars": "0.7.9",
        "ember-cli-htmlbars-inline-precompile": "^0.1.1",
        "ember-cli-ic-ajax": "0.2.1",
        "ember-cli-inject-live-reload": "^1.3.0",
        "ember-cli-qunit": "0.3.15",
        "ember-cli-release": "0.2.3",
        "ember-cli-uglify": "^1.0.1",
        "ember-data": "1.13.5",
        "ember-disable-prototype-extensions": "^1.0.0",
        "ember-disable-proxy-controllers": "^1.0.0",
        "ember-export-application-global": "^1.0.2",
        "ember-try": "0.0.6",
        "express": "^4.12.3",
        "glob": "^4.5.3",
        "jsonwebtoken": "^5.0.0",
        "morgan": "^1.5.2"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "6386f21cea0ff5da602dbe7d82455760464ebb3c",
        "tarball": "https://registry.npmjs.org/ember-cli-simple-auth-token/-/ember-cli-simple-auth-token-0.7.3.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "https://jpadilla.github.io/ember-cli-simple-auth-token/"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "231e0c695de2bf75302c95920454fb9f47a6163a",
    "homepage": "https://github.com/jpadilla/ember-cli-simple-auth-token#readme",
    "keywords": [
        "ember-addon",
        "token",
        "jwt",
        "auth",
        "authentication",
        "authorization"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jpadilla"
        },
        {
            "name": "gcollazo"
        }
    ],
    "name": "ember-cli-simple-auth-token",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jpadilla/ember-cli-simple-auth-token.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:testall"
    },
    "version": "0.7.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
