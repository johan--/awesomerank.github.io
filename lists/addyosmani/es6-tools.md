<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="addyosmani/es6-tools">addyosmani/es6-tools</a> with ranks
</p>
---
# <img src="http://i.imgur.com/yy1sACZ.png" width="100px"/> ECMAScript 6 Tools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

## Transpilers

* [Babel ★21180](babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime
* [Traceur compiler ★7280](google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.
* [es6ify ★609 ⏳2Y](thlorenz/es6ify) - Traceur compiler wrapped as a [Browserify](http://browserify.org/) v2 transform
* [babelify ★1380](babel/babelify) - Babel transpiler wrapped as a [Browserify](http://browserify.org/) transform
* [es6-transpiler ★219 ⏳1Y](termi/es6-transpiler) - ES6 > ES5. Includes classes, destructuring, default parameters, spread
* Square's [es6-module-transpiler ★1228 ⏳1Y](esnext/es6-module-transpiler) - ES6 modules to AMD or CJS
* Facebook's [regenerator ★1937](facebook/regenerator) - transform ES6 yield/generator functions to ES5
* Facebook's [jstransform ★439](facebookarchive/jstransform) - A simple utility for pluggable JS syntax transforms. Comes with a small set of ES6 -> ES5 transforms
* [defs ★120 ⏳1Y](olov/defs) - ES6 block-scoped const and let variables to ES3 vars
* [es6_module_transpiler-rails ★87 ⏳2Y](DavyJonesLocker/es6_module_transpiler-rails) - ES6 Modules in the Rails Asset Pipeline
* [Some Sweet.js macros ★222 ⏳2Y](jlongster/es6-macros) that compile from ES6 to ES5
* Bitovi's [transpile ★17](stealjs/transpile) - Converts ES6 to AMD, CJS, and StealJS.
* [regexpu ★109](mathiasbynens/regexpu) — Transform Unicode-aware ES6 regular expressions to ES5
* [Lebab](https://github.com/mohebifar/lebab) - Transformations for ES5 code to ES6 (approximates)

## Build-time transpilation

### Gulp Plugins
* Babel: [gulp-babel ★933](babel/gulp-babel)
* Traceur: [gulp-traceur ★181 ⏳1Y](sindresorhus/gulp-traceur)
* Regenerator: [gulp-regenerator ★19 ⏳1Y](sindresorhus/gulp-regenerator)
* ES6 Module Transpiler: [gulp-es6-module-transpiler ★61 ⏳1Y](ryanseddon/gulp-es6-module-transpiler)
* es6-transpiler: [gulp-es6-transpiler ★48 ⏳1Y](sindresorhus/gulp-es6-transpiler) - ES6 → ES5
* es6-jstransform: [gulp-jstransform](https://github.com/hemanth/gulp-jstransform) - ES6 → ES5 using FB's [jstransform](https://github.com/facebook/jstransform)
* regexpu: [gulp-regexpu ★4 ⏳2Y](mathiasbynens/gulp-regexpu)
* TypeScript: [gulp-typescript ★561](ivogabe/gulp-typescript)

### Grunt Tasks
* Babel: [grunt-babel ★360](babel/grunt-babel) - Turn ES6+ code into vanilla ES5 with no runtime
* Traceur: [grunt-traceur](https://github.com/aaronfrost/grunt-traceur) ES6 > ES5 transpilation, [grunt-traceur-build ★9 ⏳1Y](tarruda/grunt-traceur-build)
* ES6 Module Transpiler: [grunt-es6-module-transpiler ★86 ⏳1Y](joefiorini/grunt-es6-module-transpiler)
* Regenerator: [grunt-regenerator ★20](sindresorhus/grunt-regenerator) - ES6 generator functions to ES5
* [grunt-microlib ★29 ⏳3Y](thomasboyt/grunt-microlib) - tools for libs using ES6 module transpiler (sample [Gruntfile](https://github.com/jakearchibald/es6-promise/blob/c3336087fffc52e66cf5398e5b56b23a291080fc/Gruntfile.js))
* [grunt-defs ★4](EE/grunt-defs) - ES6 block scoped const and let variables, to ES3
* es6-transpiler: [grunt-es6-transpiler ★12 ⏳1Y](sindresorhus/grunt-es6-transpiler) - ES6 → ES5
* TypeScript: [grunt-ts ★262](TypeStrong/grunt-ts) - ES6+ > ES5/ES3 transpilation

### Broccoli Plugins
* Babel: [broccoli-babel-transpiler ★43](babel/broccoli-babel-transpiler)
* Traceur: [broccoli-traceur ★30 ⏳1Y](sindresorhus/broccoli-traceur)
* Regenerator: [broccoli-regenerator ★7 ⏳1Y](sindresorhus/broccoli-regenerator)
* ES6 Transpiler: [broccoli-transpiler ★11 ⏳1Y](sindresorhus/broccoli-es6-transpiler)
* ES6 Module Transpiler: [broccoli-es6-module-transpiler ★5 ⏳2Y](mmun/broccoli-es6-module-transpiler)
* ES6 fat arrow transpiler: [broccoli-es6-arrow](https://github.com/hemanth/broccoli-es6-arrow.git)
* TypeScript: [broccoli-tsc ★1 ⏳2Y](ngParty/broccoli-tsc)

### Brunch Plugins
* Babel: [babel-brunch ★55](babel/babel-brunch)
* ES6 Module Transpiler: [es6-module-transpiler-brunch ★8 ⏳3Y](gcollazo/es6-module-transpiler-brunch)
* TypeScript: [typescript-brunch](https://github.com/joshheyse/typescript-brunch)

## Webpack plugins
* Babel: [babel-loader ★1852](babel/babel-loader)
* Traceur: [traceur-compiler-loader ★5 ⏳2Y](gdi2290/traceur-compiler-loader)
* TypeScript: [awesome-typescript-loader ★821](s-panferov/awesome-typescript-loader)

## Duo plugins
* Babel: [duo-babel ★15 ⏳1Y](babel/duo-babel)
* TypeScript: [duo-typescript ★0 ⏳1Y](frankwallis/duo-typescript)

## Connect plugins
* Babel: [babel-connect ★22](babel/babel-connect)
* TypeScript: [typescript-middleware ★8](brn/typescript-middleware)

## Gobble plugins
* Babel: [gobble-babel ★6 ⏳1Y](babel/gobble-babel)
* Traceur: [gobble-es6-transpiler ★1 ⏳2Y](gobblejs/gobble-es6-transpiler)

## Jade plugins
* Babel: [jade-babel ★42 ⏳1Y](babel/jade-babel)
* Traceur: [jade-traceur](https://www.npmjs.com/package/jade-traceur)

## Jest plugins
* Babel: [babel-jest ★123 ⏳1Y](babel/babel-jest)

## Karma plugins
* Babel: [karma-babel-preprocessor ★138 ⏳1Y](babel/karma-babel-preprocessor)
* Traceur: [karma-traceur-preprocessor ★15 ⏳1Y](karma-runner/karma-traceur-preprocessor)
* TypeScript: [karma-typescript-preprocessor ★38](sergeyt/karma-typescript-preprocessor)

## Sprockets plugins
* Babel: [sprockets-es6](https://github.com/josh/sprockets-es6)
* Traceur: [sprockets-traceur ★25 ⏳1Y](gunpowderlabs/sprockets-traceur)
* TypeScript: [typescript-rails ★206](typescript-ruby/typescript-rails)

## Browser plugins
* [Scratch JS ★329](richgilbank/Scratch-JS) - A Chrome/Opera DevTools extension to run ES6 on a page with either Babel or Traceur
* [generator-typescript ★21](mrkev/generator-typescript) - Yeoman generator for TypeScript apps

## Mocha plugins
* [Mocha Traceur ★16](domenic/mocha-traceur) - A simple plugin for Mocha to pass JS files through the Traceur compiler

## Module Loaders

* ES6 [Module Loader polyfill](https://github.com/ModuleLoader/es6-module-loader) (compat with latest spec and Traceur)
* [js-loaders ★56 ⏳3Y](jorendorff/js-loaders) - Mozilla's spec-compliant loader prototype
* [JSPM](http://jspm.io/) - ES6, AMD, CJS module loading/package management
* [Babel Module Loader ★1852](babel/babel-loader)
* [beck.js ★5 ⏳3Y](unscriptable/beck) - toolkit for ES6 Module Loader pipelines, shim for legacy environments

## Boilerplates
* [es6-boilerplate ★86 ⏳2Y](davidjnelson/es6-boilerplate) - Tooling to allow the community to use es6 now via traceur in conjunction with amd and browser global modules, with source maps, concatenation, minification, compression, and unit testing in real browsers.
* [es6-jspm-gulp-boilerplate ★146](alexweber/es6-jspm-gulp-boilerplate) - Tooling to allow the community to use es6 now via babel in conjunction jspm, with source maps, concatenation, minification, compression, and unit testing in real browsers using es6.

## Code generation

* [generator-node-esnext ★4 ⏳2Y](briandipalma/generator-node-esnext) - Yeoman generator for Traceur apps
* [generator-es6-babel ★10 ⏳1Y](HenriqueLimas/generator-es6-babel) - Yeoman generator for Babel apps
* [generator-gulp-babelify ★2 ⏳1Y](HenriqueLimas/generator-gulp-babelify) - Yeoman generator for [Babel](https://babeljs.io/), [Browserify](http://browserify.org/) and [Gulp](http://gulpjs.com/)
* [grunt-init-es6](https://www.npmjs.com/package/grunt-init-es6) - scaffold node modules with unit tests, authored in ES6
* [Loom generators with ES6 ember modules ★15 ⏳3Y](ryanflorence/loom-generators-ember)
* Brunch [plugin](https://www.npmjs.com/package/es6-module-transpiler-brunch) for ES6 module transpilation

## Polyfills

* [core-js](https://github.com/zloirock/core-js) - Modular and compact polyfills for ES6 including Symbols, Map, Set, Iterators, Promises, setImmediate, Array generics, etc. The standard library used by [Babel ★21180](babel/babel).
* [es6-shim ★2219](paulmillr/es6-shim) - almost all new ES6 methods — from Map, Set, String, Array, Object, Object.is and more.
* [WeakMap, Map, Set, HashMap - ES6 Collections ★141](Benvie/harmony-collections)
* Polymer's [WeakMap shim ★40 ⏳2Y](Polymer/WeakMap)
* [`String.prototype.startsWith` ★71](mathiasbynens/String.prototype.startsWith)
* [`String.prototype.endsWith` ★22 ⏳2Y](mathiasbynens/String.prototype.endsWith)
* [`String.prototype.at` ★35 ⏳2Y](mathiasbynens/String.prototype.at)
* [`String.prototype.repeat` ★25 ⏳1Y](mathiasbynens/String.prototype.repeat)
* [`String.prototype.includes` ★53 ⏳1Y](mathiasbynens/String.prototype.includes)
* [`String.prototype.codePointAt` ★32 ⏳2Y](mathiasbynens/String.prototype.codePointAt)
* [`String.fromCodePoint` ★37 ⏳2Y](mathiasbynens/String.fromCodePoint)
* [`Array.prototype.find` ★27](paulmillr/Array.prototype.find)
* [`Array.prototype.findIndex` ★22](paulmillr/Array.prototype.findIndex)
* [`Array.from` ★46](mathiasbynens/Array.from)
* [`Array.of` ★11 ⏳1Y](mathiasbynens/Array.of)
* [`Object.assign` ★637](sindresorhus/object-assign)
* [`Number.isFinite` ★7](sindresorhus/is-finite)
* [`Math.sign` ★6](sindresorhus/math-sign)
* [`RegExp.prototype.match` ★8 ⏳2Y](mathiasbynens/RegExp.prototype.match)
* [`RegExp.prototype.search` ★5 ⏳2Y](mathiasbynens/RegExp.prototype.search)
* [es6-promise](https://github.com/jakearchibald/es6-promise) - polyfill for Promises matching the ES6 API
* [ES6 Map Shim ★18 ⏳2Y](eriwen/es6-map-shim) - destructive shim that follows the latest specification as closely as possible.
* [`Function.create` ★7 ⏳4Y](walling/Function.create.js)
* [ES6 shim](https://github.com/inexorabletash/polyfill/blob/master/es6.md)
* [ES6 Symbol polyfill ★83](medikoo/es6-symbol)
* [ES6 Map, Set, WeakMap ★5 ⏳1Y](EliSnow/Blitz-Collections)
* [harmony-reflect ★340](tvcutsem/harmony-reflect) - ES6 [reflection module](http://wiki.ecmascript.org/doku.php?id=harmony:reflect_api) (contains the [Proxy API](http://soft.vub.ac.be/~tvcutsem/proxies/))
* [ES5 based shims in pure CJS style](https://gist.github.com/medikoo/102b7d0e697627133788#list-of-ecmascript-6-shims) -  Array, Object, Number, Math and String functions/methods, plus Map, Set, Symbol and WeakMap objects

## Editors

* ES6 syntax highlighting for [Sublime Text and TextMate ★492](Benvie/JavaScriptNext.tmLanguage)
* ES6 syntax support in [WebStorm](https://www.jetbrains.com/webstorm/) and [PhpStorm](https://www.jetbrains.com/phpstorm/), compilation to ES5 with [file watchers or task runners](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)
* DocPad [plugin ★2 ⏳1Y](pflannery/docpad-plugin-traceur) for Traceur
* Grammar and transpilation [package ★296](gandm/language-babel)  for [Atom](https://atom.io/)
* Learn ES6 transpilation options in Webstorm [Read Blog Post](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)

## Parsers

* [Esprima](http://esprima.org) - JavaScript parser supporting ES6, parses to [ESTree AST format ★1180](estree/estree)
* [Acorn ★2496](ternjs/acorn) - A small, fast, JavaScript-based JavaScript parser with ES6 support, parses to [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) format.
* [esparse ★97](zenparsing/esparse) - ES6 parser written in ES6.
* [Traceur compiler ★7280](google/traceur-compiler) also has built-in parser available under `traceur.syntax.Parser`.

## Other

* [ES.next showcase ★312](sindresorhus/esnext-showcase) - real-world usage examples of ES6 features
* [looper ★16 ⏳3Y](wycats/looper) - static analysis tools for ES6
* [es6-module-packager](https://www.npmjs.com/package/es6-module-packager)
* [es-dependency-graph](https://github.com/yahoo/es-dependency-graph) and [grunt-es-dependency-graph ★3 ⏳2Y](yahoo/grunt-es-dependency-graph) - Generate a list of imports and exports from ES6 module files, useful for preloading, bundling, etc.
* [es6-import-validate](https://github.com/sproutsocial/es6-import-validate) and [grunt-es6-import-validate ★3 ⏳1Y](sproutsocial/grunt-es6-import-validate) - validate matching named/default import statements in ES6 modules.
* [let-er ★125 ⏳2Y](getify/let-er) - transpiles [let-block block-scoping](http://wiki.ecmascript.org/doku.php?id=proposals:block_expressions#let_statement) (not accepted into ES6) into either ES3 or ES6
* [Recast](https://github.com/benjamn/recast) - Esprima-based JavaScript syntax tree transformer, conservative pretty-printer, and automatic source map generator. Used by several of the transpilers listed above, including [regenerator](https://github.com/facebook/regenerator) and [es6-arrow-function ★51 ⏳2Y](esnext/es6-arrow-function).
* [Paws on ES6 ★279](hemanth/paws-on-es6) -  Minimalist examples of ES6 functionalities.
* [ES6 on node](http://h3manth.com/new/blog/2013/es6-on-nodejs/) - How to use ES6 features in node.js.
* [es6-translate ★5 ⏳2Y](calvinmetcalf/es6-translate) - Uses the ES6 loader hooks to load (node flavored) commonjs packages in ES6.
* [Isparta ★632](douglasduteil/isparta)
* [babel-node](https://babeljs.io/docs/usage/cli/#babel-node) - Run node cli with ES6 transpiling using Babel.
* [ES6 Lab setup ★28](hemanth/es6-lab-setup) - A simple setup for transpiling ES6 to ES5 using `Babel` or `traceur` with `gulp` and `jasmine` support.
* [TypeScript](http://www.typescriptlang.org/) - A superset of ECMAScript with strict typing that aims to align with ES6
* [Rollup](http://rollupjs.org/) - Rollup is a next-generation JavaScript module bundler. Author your app or library using ES2015 modules, then efficiently bundle them up into a single file for use in browsers and Node.js
---
<p align="center">
	This list is a copy of <a href="addyosmani/es6-tools">addyosmani/es6-tools</a> with ranks
</p>
