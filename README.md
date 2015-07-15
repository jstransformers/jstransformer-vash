# jstransformer-vash

[Vash](http://github.com/kirbysayshi/vash) support for [JSTransformers](http://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-vash/master.svg)](https://travis-ci.org/jstransformers/jstransformer-vash)
[![Coverage Status](https://img.shields.io/coveralls/jstransformers/jstransformer-vash/master.svg)](https://coveralls.io/r/jstransformers/jstransformer-vash?branch=master)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-vash/master.svg)](http://david-dm.org/jstransformers/jstransformer-vash)
[![NPM version](https://img.shields.io/npm/v/jstransformer-vash.svg)](https://www.npmjs.org/package/jstransformer-vash)

## Installation

    npm install jstransformer-vash

## API

```js
var vash = require('jstransformer')(require('jstransformer-vash'))

vash.render('Hello, @model.name!').body
//=> 'Hello, World!'
```

## License

MIT
