# npmtest-airbrake

#### basic test coverage for  [airbrake (v2.0.0)](https://github.com/airbrake/node-airbrake)  [![npm package](https://img.shields.io/npm/v/npmtest-airbrake.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-airbrake) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-airbrake.svg)](https://travis-ci.org/npmtest/node-npmtest-airbrake)

#### A Node.js notifier for Airbrake, the leading exception reporting service.

[![NPM](https://nodei.co/npm/airbrake.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/airbrake)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-airbrake/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-airbrake/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-airbrake/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-airbrake/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-airbrake/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-airbrake/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-airbrake/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-airbrake/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-airbrake/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-airbrake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-airbrake/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-airbrake/build/test-report.html](https://npmtest.github.io/node-npmtest-airbrake/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-airbrake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-airbrake/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-airbrake/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-airbrake/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-airbrake/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-airbrake/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-airbrake/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-airbrake/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Airbrake Technologies, Inc.",
    "contributors": [
        "Felix Geisendörfer <felix@debuggable.com> (http://debuggable.com/)",
        "László Bácsi <lackac@lackac.hu> (http://lackac.hu)",
        "Carlos Brito Lage <carlos@carloslage.net> (http://carloslage.net)",
        "Stephen Celis <me@stephencelis.com> (http://stephencelis.com)",
        "Sascha Depold <sascha@depold.com> (http://depold.com)",
        "Jon Keating <jon@licq.org> (http://www.thejon.org)",
        "Gabriel Lesperance <gabriel@wavo.me> (http://blog.wavo.me)",
        "Mathias Pettersson <mape@mape.me> (https://github.com/mape)",
        "Gary Rafferty <gary.rafferty@gmail.com> (http://www.garyrafferty.com)",
        "Rob Scott <rob.scott87@gmail.com> (http://lifekraze.com/rob)",
        "Dylan Smith <Dylan.Smith@shopify.com> (https://github.com/dylanahsmith)",
        "stefounet <s@fasterize.com> (http://fasterize.com)",
        "sreuter <s.reuter@geek-it.de> (https://github.com/sreuterairbrake.io",
        "Johnny Halife <johnny.halife@me.com> (http://johnny.io)"
    ],
    "name": "airbrake",
    "description": "A Node.js notifier for Airbrake, the leading exception reporting service.",
    "version": "2.0.0",
    "homepage": "https://github.com/airbrake/node-airbrake",
    "repository": {
        "type": "git",
        "url": "git://github.com/airbrake/node-airbrake.git"
    },
    "main": "./index",
    "engines": {
        "node": "*"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "test/run.js",
        "posttest": "npm run lint"
    },
    "dependencies": {
        "lodash.merge": "^4.6.0",
        "request": "^2.81.0",
        "stack-trace": "^0.0.9"
    },
    "devDependencies": {
        "eslint": "~2.8.0",
        "eslint-config-airbnb-base": "~1.0.3",
        "eslint-plugin-import": "~1.6.1",
        "express": "~4.13.4",
        "far": "~0.0.4",
        "hapi": "~13.5.0",
        "mockery": "~1.4.0",
        "nock": "^8.0.0",
        "semver": "~5.3.0",
        "sinon": "~1.7.2"
    },
    "optionalDependencies": {},
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
