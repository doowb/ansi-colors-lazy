# ansi-colors-lazy [![NPM version](https://img.shields.io/npm/v/ansi-colors-lazy.svg?style=flat)](https://www.npmjs.com/package/ansi-colors-lazy) [![NPM monthly downloads](https://img.shields.io/npm/dm/ansi-colors-lazy.svg?style=flat)](https://npmjs.org/package/ansi-colors-lazy)  [![NPM total downloads](https://img.shields.io/npm/dt/ansi-colors-lazy.svg?style=flat)](https://npmjs.org/package/ansi-colors-lazy) [![Linux Build Status](https://img.shields.io/travis/doowb/ansi-colors-lazy.svg?style=flat&label=Travis)](https://travis-ci.org/doowb/ansi-colors-lazy) [![Windows Build Status](https://img.shields.io/appveyor/ci/doowb/ansi-colors-lazy.svg?style=flat&label=AppVeyor)](https://ci.appveyor.com/project/doowb/ansi-colors-lazy)

> Lazyily loaded collection of ansi colors and styles.

## Install
Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save ansi-colors-lazy
```

## Why was this module created?

This module was created to make it easy to allow color configuration through options. If your application will always use specific colors, we recommend requiring [those modules](#related-projects) directly. If your application requires using most of the colors, we recommend using [ansi-colors][] for faster require times (the colors are inlined). When using only a few colors at a time or allowing users to choose from a few colors, this module will be more efficient due to lazy caching the [underlying modules](#related-projects).

## Usage

```js
var colors = require('ansi-colors-lazy');
```

## API

### [bgblack](index.js#L47)
Wrap a string with ansi codes to create a black background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bgblack('some string'));
```

### [bgblue](index.js#L62)
Wrap a string with ansi codes to create a blue background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bgblue('some string'));
```

### [bgcyan](index.js#L77)
Wrap a string with ansi codes to create a cyan background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bgcyan('some string'));
```

### [bggreen](index.js#L92)
Wrap a string with ansi codes to create a green background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bggreen('some string'));
```

### [bgmagenta](index.js#L107)
Wrap a string with ansi codes to create a magenta background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bgmagenta('some string'));
```

### [bgred](index.js#L122)
Wrap a string with ansi codes to create a red background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bgred('some string'));
```

### [bgwhite](index.js#L137)
Wrap a string with ansi codes to create a white background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bgwhite('some string'));
```

### [bgyellow](index.js#L152)
Wrap a string with ansi codes to create a yellow background.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bgyellow('some string'));
```

### [black](index.js#L167)
Wrap a string with ansi codes to create black text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.black('some string'));
```

### [blue](index.js#L182)
Wrap a string with ansi codes to create blue text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.blue('some string'));
```

### [bold](index.js#L197)
Wrap a string with ansi codes to create bold text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.bold('some string'));
```

### [cyan](index.js#L212)
Wrap a string with ansi codes to create cyan text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.cyan('some string'));
```

### [dim](index.js#L227)
Wrap a string with ansi codes to create dim text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.dim('some string'));
```

### [gray](index.js#L242)
Wrap a string with ansi codes to create gray text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.gray('some string'));
```

### [green](index.js#L257)
Wrap a string with ansi codes to create green text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.green('some string'));
```

### [grey](index.js#L272)
Wrap a string with ansi codes to create grey text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.grey('some string'));
```

### [hidden](index.js#L287)
Wrap a string with ansi codes to create hidden text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.hidden('some string'));
```

### [inverse](index.js#L302)
Wrap a string with ansi codes to create inverse text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.inverse('some string'));
```

### [italic](index.js#L317)
Wrap a string with ansi codes to create italic text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.italic('some string'));
```

### [magenta](index.js#L332)
Wrap a string with ansi codes to create magenta text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.magenta('some string'));
```

### [red](index.js#L347)
Wrap a string with ansi codes to create red text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.red('some string'));
```

### [reset](index.js#L362)
Wrap a string with ansi codes to reset ansi colors currently on the string.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.reset('some string'));
```

### [strikethrough](index.js#L377)
Wrap a string with ansi codes to add a strikethrough to the text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.strikethrough('some string'));
```

### [underline](index.js#L392)
Wrap a string with ansi codes to underline the text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.underline('some string'));
```

### [white](index.js#L407)
Wrap a string with ansi codes to create white text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.white('some string'));
```

### [yellow](index.js#L422)
Wrap a string with ansi codes to create yellow text.

**Params**

* `str` **{String}**: String to wrap with ansi codes.    
* `returns` **{String}**: Wrapped string  

**Example**

```js
console.log(colors.yellow('some string'));
```

## About
### Related projects
- [ansi-bgblack](https://www.npmjs.com/package/ansi-bgblack): The color bgblack, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bgblack "The color bgblack, in ansi.")
- [ansi-bgblue](https://www.npmjs.com/package/ansi-bgblue): The color bgblue, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bgblue "The color bgblue, in ansi.")
- [ansi-bgcyan](https://www.npmjs.com/package/ansi-bgcyan): The color bgcyan, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bgcyan "The color bgcyan, in ansi.")
- [ansi-bggreen](https://www.npmjs.com/package/ansi-bggreen): The color bggreen, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bggreen "The color bggreen, in ansi.")
- [ansi-bgmagenta](https://www.npmjs.com/package/ansi-bgmagenta): The color bgmagenta, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bgmagenta "The color bgmagenta, in ansi.")
- [ansi-bgred](https://www.npmjs.com/package/ansi-bgred): The color bgred, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bgred "The color bgred, in ansi.")
- [ansi-bgwhite](https://www.npmjs.com/package/ansi-bgwhite): The color bgwhite, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bgwhite "The color bgwhite, in ansi.")
- [ansi-bgyellow](https://www.npmjs.com/package/ansi-bgyellow): The color bgyellow, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bgyellow "The color bgyellow, in ansi.")
- [ansi-black](https://www.npmjs.com/package/ansi-black): The color black, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-black "The color black, in ansi.")
- [ansi-blue](https://www.npmjs.com/package/ansi-blue): The color blue, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-blue "The color blue, in ansi.")
- [ansi-bold](https://www.npmjs.com/package/ansi-bold): The color bold, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-bold "The color bold, in ansi.")
- [ansi-cyan](https://www.npmjs.com/package/ansi-cyan): The color cyan, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-cyan "The color cyan, in ansi.")
- [ansi-dim](https://www.npmjs.com/package/ansi-dim): The color dim, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-dim "The color dim, in ansi.")
- [ansi-gray](https://www.npmjs.com/package/ansi-gray): The color gray, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-gray "The color gray, in ansi.")
- [ansi-green](https://www.npmjs.com/package/ansi-green): The color green, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-green "The color green, in ansi.")
- [ansi-grey](https://www.npmjs.com/package/ansi-grey): The color grey, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-grey "The color grey, in ansi.")
- [ansi-hidden](https://www.npmjs.com/package/ansi-hidden): The color hidden, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-hidden "The color hidden, in ansi.")
- [ansi-inverse](https://www.npmjs.com/package/ansi-inverse): The color inverse, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-inverse "The color inverse, in ansi.")
- [ansi-italic](https://www.npmjs.com/package/ansi-italic): The color italic, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-italic "The color italic, in ansi.")
- [ansi-magenta](https://www.npmjs.com/package/ansi-magenta): The color magenta, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-magenta "The color magenta, in ansi.")
- [ansi-red](https://www.npmjs.com/package/ansi-red): The color red, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-red "The color red, in ansi.")
- [ansi-reset](https://www.npmjs.com/package/ansi-reset): The color reset, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-reset "The color reset, in ansi.")
- [ansi-strikethrough](https://www.npmjs.com/package/ansi-strikethrough): The color strikethrough, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-strikethrough "The color strikethrough, in ansi.")
- [ansi-underline](https://www.npmjs.com/package/ansi-underline): The color underline, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-underline "The color underline, in ansi.")
- [ansi-white](https://www.npmjs.com/package/ansi-white): The color white, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-white "The color white, in ansi.")
- [ansi-yellow](https://www.npmjs.com/package/ansi-yellow): The color yellow, in ansi. | [homepage](https://github.com/jonschlinkert/ansi-yellow "The color yellow, in ansi.")

### Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Contributors

### Release history

### Building docs
_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

### Running tests

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

### Author
**Brian Woodward**

+ [github/doowb](https://github.com/doowb)
+ [twitter/doowb](https://twitter.com/doowb)

### License
Copyright © 2017, [Brian Woodward](https://github.com/doowb).
Released under the [MIT License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on December 06, 2017._

[ansi-colors]: https://github.com/doowb/ansi-colors