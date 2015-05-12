# emojis-unicode

[![Dependency status](http://img.shields.io/david/Kikobeats/emojis-unicode.svg?style=flat-square)](https://david-dm.org/Kikobeats/emojis-unicode)
[![Dev Dependencies Status](http://img.shields.io/david/dev/Kikobeats/emojis-unicode.svg?style=flat-square)](https://david-dm.org/Kikobeats/emojis-unicode#info=devDependencies)
[![NPM Status](http://img.shields.io/npm/dm/emojis-unicode.svg?style=flat-square)](https://www.npmjs.org/package/emojis-unicode)
[![Gittip](http://img.shields.io/gittip/Kikobeats.svg?style=flat-square)](https://www.gittip.com/Kikobeats/)

> Complete list of standard Unicode codes that represent emojis.

The file content all shortcuts declared that you can use for invoke a emoji.

## Install

```bash
npm install emojis-unicode --save
```

If you want to use in the browser (powered by [Browserify](http://browserify.org/)):

```bash
bower install emojis-unicode --save
```

and later link in your HTML:

```html
<script src="bower_components/emojis-unicode/dist/emojis-unicode.js"></script>
```

## Usage

```
var emojis = require('emojis-unicode');
console.log(emojis[0]);
// => 1f004
```

## Related

* [is-emoji-keyword](https://github.com/Kikobeats/is-emoji-keyword) – Check if a word is a emoji shortcut.
* [trim-emoji](https://github.com/Kikobeats/trim-emoji) – Deletes ':' from the begin and the end of an emoji shortcut.
* [emojis-unicode](https://github.com/Kikobeats/emojis-unicode) – Complete list of standard Unicode codes that represent emojis.

## License

MIT © [Kiko Beats](http://www.kikobeats.com)
