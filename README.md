# Media Block

[![npm version](http://img.shields.io/npm/v/elr-scss-media-block.svg)](https://www.npmjs.org/package/elr-scss-media-block)
[![CI](https://github.com/Beth3346/elr-scss-media-block/actions/workflows/node.js.yml/badge.svg)](https://github.com/Beth3346/elr-scss-media-block/actions/workflows/node.js.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-media-block.svg?style=flat)](https://npmjs.com/package/elr-scss-media-block)

a library of sass mixins

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-media-block --save
```

or

```sh
yarn add elr-scss-media-block
```

## Documentation

```scss
.media-block {
  @include elr-media-block;
}
```

```scss
.media-block-noborder {
  @include elr-media-block(
    $config: (
      border-color: transparent,
      vertical-align: center,
      background-color: #eee,
      border-radius: 0,
      box-shadow: none,
    )
  );
}
```

## License

SEE LICENSE IN LICENSE.md
