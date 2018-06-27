# Awesome js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of delightful js

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.


### Utility

- [arrify](https://github.com/sindresorhus/arrify) - Turn anything into an array :star:

### HTML

- [entities](https://github.com/fb55/entities) - encode/decode entities
```
	var entities = require("entities");
	//encoding
	entities.encodeXML("&#38;");  // "&amp;#38;"
	entities.encodeHTML("&#38;"); // "&amp;&num;38&semi;"
	//decoding
	entities.decodeXML("asdf &amp; &#xFF; &#xFC; &apos;");  // "asdf & ÿ ü '"
	entities.decodeHTML("asdf &amp; &yuml; &uuml; &apos;"); // "asdf & ÿ ü '"
```


### React


### Web tools

- [codesandbox.io](https://codesandbox.io) - Online ide
- [npms.io](https://npms.io/) - alternative NPM search

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
