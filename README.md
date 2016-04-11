# map-cache [![NPM version](https://img.shields.io/npm/v/map-cache.svg?style=flat)](https://www.npmjs.com/package/map-cache) [![NPM downloads](https://img.shields.io/npm/dm/map-cache.svg?style=flat)](https://npmjs.org/package/map-cache) [![Build Status](https://img.shields.io/travis/jonschlinkert/map-cache.svg?style=flat)](https://travis-ci.org/jonschlinkert/map-cache)

> Basic cache object for storing key-value pairs.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install map-cache --save
```

# map-cache [![NPM version](https://img.shields.io/npm/v/map-cache.svg?style=flat)](https://www.npmjs.com/) [![Build Status](https://img.shields.io/travis/jonschlinkert/map-cache.svg?style=flat)](https://www.npmjs.com/package/map-cache)

> Basic cache object for storing key-value pairs.

Based on MapCache in Lo-dash v3.0.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install map-cache --save
```

## Similar projects

* [cache-base](https://www.npmjs.com/package/cache-base): Basic object cache with `get`, `set`, `del`, and `has` methods for node.js/javascript projects. | [homepage](https://github.com/jonschlinkert/cache-base)
* [config-cache](https://www.npmjs.com/package/config-cache): General purpose JavaScript object storage methods. | [homepage](https://github.com/jonschlinkert/config-cache)
* [option-cache](https://www.npmjs.com/package/option-cache): Simple API for managing options in JavaScript applications. | [homepage](https://github.com/jonschlinkert/option-cache)

## Usage

```js
var mapCache = require('map-cache');
```

## API

### [MapCache](index.js#L28)

Creates a cache object to store key/value pairs.

**Example**

```js
var cache = new MapCache();
```

### [.set](index.js#L45)

Adds `value` to `key` on the cache.

**Params**

* `key` **{String}**: The key of the value to cache.
* `value` **{any}**: The value to cache.
* `returns` **{Object}**: Returns the `Cache` object for chaining.

**Example**

```js
cache.set('foo', 'bar');
```

### [.get](index.js#L65)

Gets the cached value for `key`.

**Params**

* `key` **{String}**: The key of the value to get.
* `returns` **{any}**: Returns the cached value.

**Example**

```js
cache.get('foo');
//=> 'bar'
```

### [.has](index.js#L82)

Checks if a cached value for `key` exists.

**Params**

* `key` **{String}**: The key of the entry to check.
* `returns` **{Boolean}**: Returns `true` if an entry for `key` exists, else `false`.

**Example**

```js
cache.has('foo');
//=> true
```

### [.del](index.js#L98)

Removes `key` and its value from the cache.

**Params**

* `key` **{String}**: The key of the value to remove.
* `returns` **{Boolean}**: Returns `true` if the entry was removed successfully, else `false`.

**Example**

```js
cache.del('foo');
```

## Run tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/map-cache/issues/new).

## Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Based on MapCache in Lo-dash v3.0. [MIT License](https://github.com/lodash/lodash/blob/master/LICENSE.txt)
Released under the [MIT license](https://github.com/jonschlinkert/map-cache/blob/master/LICENSE).

***

_This file was generated by [verb](https://github.com/verbose/verb), v0.9.0, on April 11, 2016._

## Related projects

You might also be interested in these projects:

* [cache-base](https://www.npmjs.com/package/cache-base): Basic object cache with `get`, `set`, `del`, and `has` methods for node.js/javascript projects. | [homepage](https://github.com/jonschlinkert/cache-base)
* [config-cache](https://www.npmjs.com/package/config-cache): General purpose JavaScript object storage methods. | [homepage](https://github.com/jonschlinkert/config-cache)
* [option-cache](https://www.npmjs.com/package/option-cache): Simple API for managing options in JavaScript applications. | [homepage](https://github.com/jonschlinkert/option-cache)

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/map-cache/issues/new).

## Building docs

Generate readme and API documentation with [verb][]:

```sh
$ npm install verb && npm run docs
```

Or, if [verb][] is installed globally:

```sh
$ verb
```

## Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

## Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](https://github.com/jonschlinkert/map-cache/blob/master/LICENSE).

***

_This file was generated by [verb](https://github.com/verbose/verb), v0.9.0, on April 11, 2016._