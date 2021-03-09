[![GitHub forks](https://img.shields.io/badge/npm-v2.0.0-blue)](https://www.npmjs.com/package/@siddhanthmanjunath/tiny)
[![GitHub forks](https://img.shields.io/badge/minified%20size-269B-blue)](https://www.npmjs.com/package/@siddhanthmanjunath/tiny)



## tiny
removes all spaces from a string

## Install

```
$ npm install @siddhanthmanjunath/tiny
```

## Usage

```js
const tiny = require("@siddhanthmanjunath/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
