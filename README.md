# Nuxt SVG Loader - SVGs as components, also on the server side!
[![npm (scoped with tag)](https://img.shields.io/npm/v/nuxt-svg-loader/latest.svg?style=flat-square)](https://npmjs.com/package/nuxt-svg-loader)
[![npm](https://img.shields.io/npm/dt/nuxt-svg-loader.svg?style=flat-square)](https://npmjs.com/package/nuxt-svg-loader)
[![Build Status](https://travis-ci.com/Developmint/nuxt-svg-loader.svg?branch=master)](https://travis-ci.com/Developmint/nuxt-svg-loader)
[![codecov](https://codecov.io/gh/Developmint/nuxt-svg-loader/branch/master/graph/badge.svg)](https://codecov.io/gh/Developmint/nuxt-svg-loader)
[![Dependencies](https://david-dm.org/Developmint/nuxt-svg-loader/status.svg?style=flat-square)](https://david-dm.org/Developmint/nuxt-svg-loader)
[![js-standard-style](https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square)](http://standardjs.com)

>

[📖 **Release Notes**](./CHANGELOG.md)

## Features

* Full support of SVGs as components. Import them like your Vue SFCs
* Built on top of [vue-svg-loader](https://github.com/visualfanatic/vue-svg-loader)
* Nuxt 2 (and only Nuxt 2) support
* Fully tested!

## Demo

A [live demo](https://zxr9l743l3.sse.codesandbox.io/) is available through the [CodeSandBox](https://codesandbox.io/s/github/Developmint/nuxt-svg-loader/tree/master) of the repo

## Setup

- Add `nuxt-svg-loader` dependency using yarn or npm to your project
- Add `nuxt-svg-loader` to `modules` section of `nuxt.config.js`

```js
{
  modules: [
    'nuxt-svg-loader',
  ],
}
```

- No more options are needed. It'll simply work

## Development

- Clone this repository
- Install dependencies using `yarn install` or `npm install`
- Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Alexander Lichter
