# better-node-env [![Build Status](https://travis-ci.org/mvila/better-node-env.svg?branch=master)](https://travis-ci.org/mvila/better-node-env)

`NODE_ENV || 'development'` for Node and browser.

## Installation

```
npm install --save better-node-env
```

## Usage

```javascript
var environment = require('better-node-env');

console.log(environment);
```

In case you use [Browserify](http://browserify.org/), this module exports `window.NODE_ENV` (or `'development'` if `window.NODE_ENV` is undefined).

## License

MIT
