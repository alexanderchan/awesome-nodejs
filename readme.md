# Awesome js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated and slightly opinionated list of delightful js. Some other libraries I've used or considered and why I've chosen one over the other 🤷. Alternatives are all excellent and may fit one's use case.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.  

# React

### CSS in JS

- [emotion](https://emotion.sh) - Fast css in js by updating classes over direct styling

Alternative	| Why not?
--------------- | -------------
 glamourous	| see [message](https://github.com/paypal/glamorous/issues/419).  Could consider for react-native 
 [styled-components](https://www.styled-components.com) | emotion has api inspired by both glamourous and styled-components
 
### React - State management

- [unstated](https://github.com/jamiebuilds/unstated) - Simple state management.  As much as I enjoy mobx and learnt a lot from redux, unstated has a simple api to understand.  One only needs to know: pub/sub and this.setState.  Regardless of state management library choice, it is worth watching the free courses on egghead on mobx and redux as well as [Michel Westrate's talk](https://www.youtube.com/watch?v=Gyp2QDr7YkU).

Alternative	| Why not?
--------------- | -------------
 mobx		| Slightly higher learning curve and a bit more setup if using decorators.  If perf gets slow, try mobx
 redux		| More setup, probably better for a larger app but mobx should also handle the same cases.  Use with immerjs
 RxJs		| Observables are outstanding at managing complex async actions.  I tried using [acdlite's](https://github.com/acdlite/react-rx-component) but didn't work out.  If going down the rxjs route also consider [redux-observable](https://github.com/redux-observable/redux-observable)
 
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
- [arrify](https://github.com/sindresorhus/arrify) - Turn anything into an array :star:
- [entities](https://github.com/fb55/entities) - encode/decode entities

Alternative	| Why/Why not?
--------------- | -------------
 qs		| querystring only available on node and some of the qs implementations not as maintained |

- [date-fns](https://date-fns.org/) - Date functions

Alternative	| Why not?
--------------- | -------------
 moment		| larger library if including all locals and some [performance](https://raygun.com/blog/moment-js-vs-date-fns/) concerns



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
