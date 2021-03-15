# @ahuvia/tiny

[![GitHub issues](https://img.shields.io/github/issues/ahuvia/tiny)](https://github.com/ahuvia/tiny/issues)

## Install

`npm i @ahuvia/tiny`

## Example

```js
const tiny = require("@ahuvia/tiny");

tiny("So much space!");
// => "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
