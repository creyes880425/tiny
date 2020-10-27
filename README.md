# @creyes880425/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@creyes880425/tiny.svg)](https://www.npmjs.com/package/@creyes880425/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@creyes880425/tiny.svg)](https://www.npmjs.com/package/@creyes880425/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @creyes880425/tiny
```

## Usage

```js
const tiny = require("@creyes880425/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
