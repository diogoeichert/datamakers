[![code style](https://img.shields.io/badge/code_style-classic-blue.svg)](http://diogoeichert.github.io/eslint-config-classic)
[![downloads](https://img.shields.io/npm/dt/datamakers.svg)](https://www.npmjs.com/package/datamakers)
[![license](https://img.shields.io/github/license/diogoeichert/datamakers.svg)](LICENSE)
[![npm version](https://img.shields.io/npm/v/datamakers.svg)](https://www.npmjs.com/package/datamakers)

# datamakers
Factories for common data structures.

## Usage
```
const {makeEnum, makeHashSet} = require('datamakers');

const RGB = makeEnum([
  'Red',
  'Green',
  'Blue'
]);

const CMYK = makeHashSet([
  'Cyan',
  'Magenta',
  'Yellow',
  'Black'
]);
```
