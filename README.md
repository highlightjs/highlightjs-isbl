![](https://img.shields.io/badge/maintainer-needed-red?style=for-the-badge&logo=github)

This grammar has been extracted from Highlight.js and could use a new maintainer. Currently unmaintained.

---

# ISBL - a language grammar for highlight.js

![version](https://badgen.net/npm/v/highlightjs-isbl)
![license](https://badgen.net/badge/license/MIT/blue)
![compatible with v11.x](https://badgen.net/badge/compatibility/v11.x/cyan)
![install size](https://badgen.net/packagephobia/install/highlightjs-isbl) ![minified size](https://badgen.net/bundlephobia/min/highlightjs-isbl)

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

Simply load the module after loading Highlight.js.  You'll use the minified version found in the `dist` directory.  This module is just a CDN build of the language, so it will register itself as the Javascript is loaded.

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" src="/path/to/isbl.min.js"></script>
<script type="text/javascript">
  hljs.highlightAll();
</script>
```

### Using directly from the UNPKG CDN

```html
<script type="text/javascript"
  src="https://unpkg.com/highlightjs-isbl@1.0.0/dist/isbl.min.js"></script>
```

- More info: <https://unpkg.com>

### With Node or another build system

If you're using Node / Webpack / Rollup / Browserify, etc, simply require the language module, then register it with Highlight.js.

```javascript
var hljs = require('highlight.js');
var grammar = require('highlightjs-isbl');

hljs.registerLanguage("isbl", grammar);
hljs.highlightAll();
```


## License

Highlight.js is released under the MIT License. See [LICENSE][1] file
for details.

### Author

Dmitriy Tarasov <dimatar@gmail.com>

### Maintainer

This grammar has been extracted from Highlight.js and could use a new maintainer. Currently unmaintained.

![](https://img.shields.io/badge/maintainer-needed-red?style=for-the-badge&logo=github)

## Links

- The official site for the Highlight.js library is <https://highlightjs.org/>.
- The Highlight.js GitHub project: <https://github.com/highlightjs/highlight.js>

[1]: https://github.com/highlightjs/highlightjs-isbl/blob/main/LICENSE
