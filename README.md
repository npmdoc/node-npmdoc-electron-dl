# npmdoc-electron-dl

#### api documentation for  electron-dl (v1.8.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-dl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-dl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-dl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-dl)

#### Simplified file downloads for your Electron app

[![NPM](https://nodei.co/npm/electron-dl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-dl)

- [https://npmdoc.github.io/node-npmdoc-electron-dl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-dl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-dl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-dl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-dl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-dl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-dl",
    "version": "1.8.0",
    "description": "Simplified file downloads for your Electron app",
    "license": "MIT",
    "repository": "sindresorhus/electron-dl",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "scripts": {
        "start": "electron test.js",
        "test": "xo"
    },
    "files": [
        "index.js"
    ],
    "keywords": [
        "electron",
        "app",
        "file",
        "download",
        "downloader",
        "progress"
    ],
    "dependencies": {
        "pupa": "^1.0.0",
        "unused-filename": "^0.1.0"
    },
    "devDependencies": {
        "electron": "^1.3.3",
        "xo": "*"
    },
    "xo": {
        "esnext": true,
        "envs": [
            "node",
            "browser"
        ],
        "rules": {
            "import/no-extraneous-dependencies": "off"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
