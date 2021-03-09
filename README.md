[![GitHub forks](https://img.shields.io/badge/npm-v1.0.0-blue)](https://github.com/Vinecreeper888/tiny/network)
[![GitHub forks](https://img.shields.io/badge/minified%20size-entry%20point%20error-red)](https://github.com/Vinecreeper888/tiny/network)



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
