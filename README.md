# @a-2-c-2-anpm/eum-iste-perspiciatis <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Set` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-set-objects).

## Getting started

```sh
npm install --save @a-2-c-2-anpm/eum-iste-perspiciatis
```

## Usage/Examples

```js
var set = new Set();
var obj = {};

set.add(obj);

set.has(obj); // true
map.has(3); // false
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/a-2-c-2-anpm/eum-iste-perspiciatis
[npm-version-svg]: https://versionbadg.es/a-2-c-2-anpm/eum-iste-perspiciatis.svg
[deps-svg]: https://david-dm.org/a-2-c-2-anpm/eum-iste-perspiciatis.svg
[deps-url]: https://david-dm.org/a-2-c-2-anpm/eum-iste-perspiciatis
[dev-deps-svg]: https://david-dm.org/a-2-c-2-anpm/eum-iste-perspiciatis/dev-status.svg
[dev-deps-url]: https://david-dm.org/a-2-c-2-anpm/eum-iste-perspiciatis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@a-2-c-2-anpm/eum-iste-perspiciatis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@a-2-c-2-anpm/eum-iste-perspiciatis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@a-2-c-2-anpm/eum-iste-perspiciatis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@a-2-c-2-anpm/eum-iste-perspiciatis
[codecov-image]: https://codecov.io/gh/a-2-c-2-anpm/eum-iste-perspiciatis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/a-2-c-2-anpm/eum-iste-perspiciatis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/a-2-c-2-anpm/eum-iste-perspiciatis
[actions-url]: https://github.com/a-2-c-2-anpm/eum-iste-perspiciatis/actions
