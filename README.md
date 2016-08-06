# react-redux-immutable-boilerplate
STATUS: In progress

##Features
* [React](https://facebook.github.io/react/)
* [Redux](http://redux.js.org/), for simple and scalable state management
* [Immutable.js](https://facebook.github.io/immutable-js/), which seriously optimizes React performance in conjunction with:
  * [PureRenderMixin](https://facebook.github.io/react/docs/pure-render-mixin.html), which gives a huge boost to [shouldComponentUpdate]() through [shallow comparison](https://facebook.github.io/react/docs/shallow-compare.html)
  * [redux-immutable](https://github.com/gajus/redux-immutable), an implementation of Redux's [combineReducers](http://redux.js.org/docs/api/combineReducers.html) method that works with Immutable.js state
  * [react-immutable-proptypes](https://github.com/HurricaneJames/react-immutable-proptypes)
* [Babel](https://babeljs.io/), for ES6 and ES7 support
* [Webpack](http://webpack.github.io/docs/), for bundling
* [Hot Module Replacement](https://webpack.github.io/docs/hot-module-replacement.html), through [Webpack Dev Server](https://webpack.github.io/docs/webpack-dev-server.html) & [React Hot Loader](https://github.com/gaearon/react-hot-loader)
* [ESLint](http://eslint.org/), using Airbnb's popular [configuration](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb)
* [PostCSS](http://postcss.org/) for future-proof CSS, with the following plugins:
  * [PreCSS](https://github.com/jonathantneal/precss), which allows for Sass-like markup
  * [CSS Modules](https://github.com/css-modules/css-modules), so you can just name your classes intuitively
  * [CSSNext](http://cssnext.io/), for CSS4 goodies and [automated cross-browser compatibility](https://github.com/postcss/autoprefixer)
* [Mocha](http://mochajs.org/), [Chai](http://chaijs.com/), and [Sinon](http://sinonjs.org/) unit testing, with [Enzyme](http://airbnb.io/enzyme/) testing utilities for React
* [Travis CI](https://travis-ci.com/) base configuration

##Requirements
[Node.js](https://nodejs.org) v6+

