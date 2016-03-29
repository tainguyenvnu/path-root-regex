# path-root-regex [![NPM version](https://img.shields.io/npm/v/path-root-regex.svg?style=flat)](https://www.npmjs.com/package/path-root-regex) [![NPM downloads](https://img.shields.io/npm/dm/path-root-regex.svg?style=flat)](https://npmjs.org/package/path-root-regex) [![Build Status](https://img.shields.io/travis/regexhq/path-root-regex.svg?style=flat)](https://travis-ci.org/regexhq/path-root-regex)

> Regular expression for getting the root of a posix or windows filepath.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install path-root-regex --save
```

## Usage

The module exposes a function that must be called to get the regex (modified from the split device regex in the node.js path module);

```js
var pathRootRegex = require('path-root-regex');

console.log(pathRootRegex() instanceof RegExp);
//=> true
```

See the [path-root](https://github.com/jonschlinkert/path-root) module for examples.

## Related projects

You might also be interested in these projects:

* [is-absolute](https://www.npmjs.com/package/is-absolute): Polyfill for node.js `path.isAbolute`. Returns true if a file path is absolute. | [homepage](https://github.com/jonschlinkert/is-absolute)
* [parse-filepath](https://www.npmjs.com/package/parse-filepath): Parse a filepath into an object. Falls back on the native node.js `path.parse` method if… [more](https://www.npmjs.com/package/parse-filepath) | [homepage](https://github.com/jonschlinkert/parse-filepath)
* [path-root](https://www.npmjs.com/package/path-root): Get the root of a posix or windows filepath. | [homepage](https://github.com/jonschlinkert/path-root)

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/path-root-regex/issues/new).

## Building docs

Generate readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install verb && npm run docs
```

Or, if [verb](https://github.com/verbose/verb) is installed globally:

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
Released under the [MIT license](https://github.com/regexhq/path-root-regex/blob/master/LICENSE).

***

_This file was generated by [verb](https://github.com/verbose/verb), v, on March 29, 2016._