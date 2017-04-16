# test coverage for  [bcryptjs (v2.4.3)](https://github.com/dcodeIO/bcrypt.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bcryptjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bcryptjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bcryptjs.svg)](https://travis-ci.org/npmtest/node-npmtest-bcryptjs)
#### Optimized bcrypt in plain JavaScript with zero dependencies. Compatible to 'bcrypt'.

[![NPM](https://nodei.co/npm/bcryptjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bcryptjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bcryptjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bcryptjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bcryptjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bcryptjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bcryptjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bcryptjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bcryptjs/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bcryptjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bcryptjs/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-bcryptjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bcryptjs/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bcryptjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bcryptjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bcryptjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bcryptjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Wirtz"
    },
    "browser": "dist/bcrypt.js",
    "bugs": {
        "url": "https://github.com/dcodeIO/bcrypt.js/issues"
    },
    "contributors": [
        {
            "name": "Shane Girish",
            "url": "https://github.com/shaneGirish"
        },
        {
            "name": "Alex Murray",
            "url": "https://github.com/alexmurray"
        },
        {
            "name": "Nicolas Pelletier",
            "url": "https://github.com/NicolasPelletier"
        },
        {
            "name": "Josh Rogers",
            "url": "https://github.com/geekymole"
        },
        {
            "name": "Noah Isaacson",
            "url": "https://github.com/nisaacson"
        }
    ],
    "dependencies": {},
    "description": "Optimized bcrypt in plain JavaScript with zero dependencies. Compatible to 'bcrypt'.",
    "devDependencies": {
        "bcrypt": "latest",
        "closurecompiler": "~1",
        "metascript": "~0.18",
        "testjs": "~1",
        "utfx": "~1"
    },
    "directories": {},
    "dist": {
        "shasum": "9ab5627b93e60621ff7cdac5da9733027df1d0cb",
        "tarball": "https://registry.npmjs.org/bcryptjs/-/bcryptjs-2.4.3.tgz"
    },
    "gitHead": "f7dd725a0b77036696042b5c1cb5e13cf0f7291e",
    "homepage": "https://github.com/dcodeIO/bcrypt.js#readme",
    "keywords": [
        "bcrypt",
        "password",
        "auth",
        "authentication",
        "encryption",
        "crypt",
        "crypto"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dcode"
        }
    ],
    "name": "bcryptjs",
    "optionalDependencies": {},
    "repository": {
        "type": "url",
        "url": "git+https://github.com/dcodeIO/bcrypt.js.git"
    },
    "scripts": {
        "build": "node scripts/build.js",
        "compile": "node node_modules/closurecompiler/bin/ccjs dist/bcrypt.js --compilation_level=SIMPLE_OPTIMIZATIONS --create_source_map=dist/bcrypt.min.map > dist/bcrypt.min.js",
        "compress": "gzip -c -9 dist/bcrypt.min.js > dist/bcrypt.min.js.gz",
        "make": "npm run build && npm run compile && npm run compress && npm test",
        "test": "node node_modules/testjs/bin/testjs"
    },
    "version": "2.4.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
