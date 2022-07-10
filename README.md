# Infinitesimal

[![npm (scoped)](https://img.shields.io/npm/v/infinitesimal.svg)](https://www.npmjs.com/package/infinitesimal)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/infinitesimal.svg)](https://www.npmjs.com/package/infinitesimal)

Removes all blank spaces from a string.

## Install

```
$ npm install infinitesimal
```

## Usage

```js
const noSpace = require("infinitesimal");

noSpace("A lot of space here!");
//=> "Alotofspacehere!"

noSpace(82108);
//=> Uncaught TypeError: noSpace wants a string!
//    at noSpace (<anonymous>:2:41)
//    at <anonymous>:1:1
```
