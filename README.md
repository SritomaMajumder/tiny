# @sritomamajumder/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@sritomamajumder/tiny.svg)](https://www.npmjs.com/package/@sritomamajumder/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@sritomamajumder/tiny.svg)](https://www.npmjs.com/package/@sritomamajumder/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @sritomamajumder/tiny
```

## Usage

```js
const tiny = require("@sritomamajumder/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```