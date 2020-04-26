# jstransformer-vash

[Vash](http://github.com/kirbysayshi/vash) support for [JSTransformers](http://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-vash/master.svg)](https://travis-ci.org/jstransformers/jstransformer-vash)
[![Coverage Status](https://img.shields.io/codecov/c/github/jstransformers/jstransformer-vash/master.svg)](https://codecov.io/gh/jstransformers/jstransformer-vash)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-vash/master.svg)](http://david-dm.org/jstransformers/jstransformer-vash)

[![NPM version](https://img.shields.io/npm/v/jstransformer-vash.svg)](https://www.npmjs.org/package/jstransformer-vash)

## Installation

    npm install jstransformer-vash

## API

```js
var vash = require('jstransformer')(require('jstransformer-vash'))

vash.render('Hello, @model.name!', { name: 'World' }).body
//=> 'Hello, World!'
```

## License

MIT
