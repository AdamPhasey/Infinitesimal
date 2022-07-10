# infinitesinal

[![npm (scoped)](https://img.shields.io/npm/v/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/infinitesimal)
[![npm bundle size (minified)](https://img.shields.io/npm/v/infinitesimal.svg)](https://www.npmjs.com/package/infinitesimal)

Removes all spaces from a string.

## Install

```
$ npm install infinitesimal
```

## Usage

```js
const noSpace = require("infinitesimal");

noSpace("So much space!");
//=> "Somuchspace!"

noSpace(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
