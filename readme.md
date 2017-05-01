# Fabricator String toCamelCase prototype method

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

## Installing

With Fabricator and NPM, simply require this library into your project and restart the Fabricator Grunt build process.

`npm install fab.prototype.to-camel-case --save`

If you are not using Fabricator, you will need to in some manner compile `src/prototype.toCamelCase.js` into your build process or put it somewhere where you can link it into your projects.

## Usage

### `'my-string'.toCamelCase()`

Returns a camel cased string.
