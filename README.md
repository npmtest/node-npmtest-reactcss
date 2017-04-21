# npmtest-reactcss

#### basic test coverage for  reactcss (v1.2.2)  [![npm package](https://img.shields.io/npm/v/npmtest-reactcss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-reactcss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-reactcss.svg)](https://travis-ci.org/npmtest/node-npmtest-reactcss)

#### Bringing Classes to Inline Styles

[![NPM](https://nodei.co/npm/reactcss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reactcss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-reactcss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-reactcss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-reactcss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-reactcss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-reactcss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-reactcss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-reactcss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-reactcss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-reactcss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-reactcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-reactcss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-reactcss/build/test-report.html](https://npmtest.github.io/node-npmtest-reactcss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-reactcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-reactcss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-reactcss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reactcss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reactcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reactcss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-reactcss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-reactcss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "reactcss",
    "version": "1.2.2",
    "description": "Bringing Classes to Inline Styles",
    "author": "case <case@casesandberg.com>",
    "main": "lib/index.js",
    "scripts": {
        "clean": "rm -rf lib && mkdir lib",
        "lib": "npm run clean && babel src -d lib",
        "test": "npm run unit-test -s && npm run eslint -s",
        "unit-test": "node_modules/.bin/jest",
        "tdd": "node_modules/.bin/jest --watchAll",
        "docs": "webpack-dev-server --config webpack.dev.js --port 2570",
        "docs-dist": "webpack --config webpack.prod.js",
        "dev": "npm run docs",
        "prepublish": "npm run lib",
        "eslint": "node_modules/.bin/eslint src/**/*.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/casesandberg/reactcss"
    },
    "keywords": [
        "react",
        "reactcss"
    ],
    "license": "MIT",
    "dependencies": {
        "lodash": "^4.0.1"
    },
    "devDependencies": {
        "@case/eslint-config": "^0.1.4",
        "babel": "^6.0.15",
        "babel-cli": "^6.23.0",
        "babel-core": "^6.1.2",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^6.0.1",
        "babel-plugin-lodash": "^3.2.11",
        "babel-preset-es2015": "^6.1.18",
        "babel-preset-react": "^6.1.18",
        "babel-preset-stage-0": "^6.1.18",
        "babel-register": "^6.9.0",
        "css-loader": "^0.14.5",
        "highlight.js": "^8.6.0",
        "html-loader": "^0.3.0",
        "install": "^0.4.0",
        "jest": "^19.0.2",
        "jsx-loader": "^0.13.2",
        "markdown-loader": "^0.1.2",
        "normalize.css": "^3.0.3",
        "react": "^15.1.0",
        "react-context": "0.0.3",
        "react-dom": "^15.1.0",
        "react-hot-loader": "^1.2.5",
        "react-test-renderer": "^15.4.2",
        "remarkable": "^1.6.0",
        "require-dir": "^0.3.0",
        "style-loader": "^0.12.3",
        "webpack": "^1.8.11",
        "webpack-dev-server": "^1.8.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
