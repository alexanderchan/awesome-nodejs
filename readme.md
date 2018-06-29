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
Alternative	| Why/Why not?
--------------- | -------------
 qs		| querystring only available on node and some of the qs implementations not as maintained |


# React

### CSS in JS

- [emotion](https://emotion.sh) - Fast css in js by updating classes over direct styling

Alternative	| Why not?
--------------- | -------------
 glamourous	| see (message)[https://github.com/paypal/glamorous/issues/419].  Could consider for react-native 
 (styled-components)[https://www.styled-components.com] | emotion has api inspired by both glamourous and styled-components
 
### React - State management

- [unstated](https://github.com/jamiebuilds/unstated) - Simple state management.  As much as I enjoy mobx, this is easier for code handoff to understand the pub/sub and this.setState since most react devs will learn this.  

Alternative	| Why not?
--------------- | -------------
 mobx		| Slightly higher learning curve and a bit more setup if using decorators.  If perf gets slow, try mobx
 redux		| More setup, probably better for a larger app but mobx should also handle the same cases.  Use with immerjs
 
# Packaging

- [parceljs](https://parceljs.org/) - Fast re-builds

Alternative				| Why not?
--------------- 			| -------------
 [webpack](https://webpack.js.org/)	| More complex, slower, but is a bit more established


## Web tools

- [codesandbox.io](https://codesandbox.io) - Online ide
- [npms.io](https://npms.io/) - alternative NPM search


# Utils

- [lodash](https://lodash.com) - General purpose util library
- [date-fns](https://date-fns.org/) - Date functions

Alternative	| Why not?
--------------- | -------------
 moment		| larger library if including all locals and some [performance](https://raygun.com/blog/moment-js-vs-date-fns/) issues



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
