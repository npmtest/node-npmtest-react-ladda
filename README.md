# npmtest-react-ladda

#### basic test coverage for  [react-ladda (v5.0.6)](https://github.com/jsdir/react-ladda#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-ladda.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-ladda) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-ladda.svg)](https://travis-ci.org/npmtest/node-npmtest-react-ladda)

#### React wrapper for Ladda buttons

[![NPM](https://nodei.co/npm/react-ladda.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-ladda)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-ladda/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-ladda/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-ladda/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-ladda/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-ladda/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-ladda/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-ladda/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-ladda/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-ladda/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-ladda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-ladda/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-ladda/build/test-report.html](https://npmtest.github.io/node-npmtest-react-ladda/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-ladda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-ladda/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-ladda/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-ladda/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-ladda/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-ladda/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-ladda/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-ladda/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Sommer"
    },
    "bugs": {
        "url": "https://github.com/jsdir/react-ladda/issues"
    },
    "dependencies": {
        "ladda": "^1.0.0"
    },
    "description": "React wrapper for Ladda buttons",
    "devDependencies": {
        "babel-cli": "^6.14.0",
        "babel-eslint": "^6.1.2",
        "babel-plugin-transform-flow-strip-types": "^6.8.0",
        "babel-plugin-transform-regenerator": "^6.4.4",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "babel-register": "^6.4.3",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.5.1",
        "enzyme": "^2.0.0",
        "eslint": "^3.7.0",
        "eslint-config-airbnb": "^12.0.0",
        "eslint-plugin-import": "^1.16.0",
        "eslint-plugin-jsx-a11y": "^2.2.2",
        "eslint-plugin-react": "^6.3.0",
        "jsdom": "^8.0.1",
        "mocha": "^2.4.5",
        "react": "^0.14.0 || ^15.0.0",
        "react-addons-test-utils": "^15.3.1",
        "react-dom": "^0.14.0 || ^15.0.0",
        "sinon": "^1.17.5",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "648e0934dc4179baf320a4420ba1c398798f0138",
        "tarball": "https://registry.npmjs.org/react-ladda/-/react-ladda-5.0.6.tgz"
    },
    "gitHead": "a4e2b3c1d41581dbecb537395a62e89776d2d9d7",
    "homepage": "https://github.com/jsdir/react-ladda#readme",
    "keywords": [
        "react",
        "component",
        "boilerplate"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "jsdir"
        }
    ],
    "name": "react-ladda",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jsdir/react-ladda.git"
    },
    "scripts": {
        "build": "npm run lint && ./node_modules/.bin/babel src --out-dir dist",
        "lint": "eslint src/**/* test/**/*",
        "prepublish": "npm run build",
        "test": "mocha test/.setup.js test/**/*-test.jsx",
        "watch": "mocha -w --watch-extensions=jsx test/.setup.js test/**/*-test.jsx"
    },
    "version": "5.0.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
