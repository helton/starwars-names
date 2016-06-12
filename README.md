# starwars-names

[![travis build](https://img.shields.io/travis/helton/starwars-names.svg?style=flat-square)](https://travis-ci.org/helton/starwars-names)
[![codecov coverage](https://img.shields.io/codecov/c/github/helton/starwars-names.svg?style=flat-square)](https://codecov.io/gh/helton/starwars-names)
[![npm version](https://img.shields.io/npm/v/starwars-names-helton.svg?style=flat-square)](http://npm.im/starwars-names-helton)
[![npm downloads](https://img.shields.io/npm/dm/starwars-names-helton.svg?style=flat-square)](http://npm-stat.com/charts.html?package=starwars-names-helton)
[![MIT license](https://img.shields.io/npm/l/starwars-names-helton.svg?style=flat-square)](http://opensource.org/licenses/MIT)

Get random names from Star Wars characters.

## Installation

This package is distributed via npm:

```
npm install starwars-names-helton
```

## Usage

```javascript
var names = require('starwars-names-helton');
var allNames = names.all;
var randomName = names.random();
var threeRandomNames = names.random(3);
```