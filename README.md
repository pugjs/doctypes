# doctypes

Shorthands for commonly used doctypes

[![Build Status](https://img.shields.io/travis/jadejs/doctypes/master.svg)](https://travis-ci.org/jadejs/doctypes)
[![Dependency Status](https://img.shields.io/gemnasium/jadejs/doctypes.svg)](https://gemnasium.com/jadejs/doctypes)
[![NPM version](https://img.shields.io/npm/v/doctypes.svg)](https://www.npmjs.org/package/doctypes)

## Installation

    npm install doctypes

## Usage

```js
var assert = require('assert');
var doctypes = require('doctypes');

assert(doctypes['html'] === '<!DOCTYPE html>');
assert(doctypes['xml'] === '<?xml version="1.0" encoding="utf-8" ?>');
```

## License

  MIT
