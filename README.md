# Math.atanh <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.atanh` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @diotoborg/fuga-molestias
```

## Usage/Examples

```js
console.log(Math.atanh(-1)); // -Infinity
console.log(Math.atanh(0)); // 0
console.log(Math.atanh(0.5)); // 0.5493061443340548
console.log(Math.atanh(2)); // NaN
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@diotoborg/fuga-molestias
[npm-version-svg]: https://versionbadg.es/@diotoborg/fuga-molestias.svg
[deps-svg]: https://david-dm.org/diotoborg/fuga-molestias.svg
[deps-url]: https://david-dm.org/diotoborg/fuga-molestias
[dev-deps-svg]: https://david-dm.org/diotoborg/fuga-molestias/dev-status.svg
[dev-deps-url]: https://david-dm.org/diotoborg/fuga-molestias#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/fuga-molestias.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/fuga-molestias.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/fuga-molestias.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/fuga-molestias
[codecov-image]: https://codecov.io/gh/diotoborg/fuga-molestias/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/diotoborg/fuga-molestias/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/diotoborg/fuga-molestias
[actions-url]: https://github.com/diotoborg/fuga-molestias/actions
