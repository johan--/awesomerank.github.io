<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="addyosmani/critical-path-css-tools">addyosmani/critical-path-css-tools</a> with ranks
</p>
---
Critical-path (Above-the-fold) CSS Tools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)
==========================================

> Tools to help prioritize above-the-fold CSS

### Prioritize above-the-fold content first.

For best performance, PageSpeed Insights [recommends](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent) inlining the critical (above-the-fold) CSS of your page directly into your HTML. This eliminates additional roundtrips and allows the browser to paint the above-fold experience to your user's screen sooner. The main idea is:

* Determine the above-the-fold styles for a page and write them between `<style>` tags in the head.
* Load all other stylesheets in the footer, ideally asynchronously.

The following is a list of tools to help generate, inline and report on critical-path CSS.

## Node modules


* [Penthouse ★1412](pocketjoso/penthouse) - by Jonas Ohlsson generates critical-path CSS
* [Critical](https://github.com/addyosmani/critical) - by Addy Osmani generates & inlines critical-path CSS (uses Penthouse, [Oust ★115](addyosmani/oust) and inline-styles)
* [CriticalCSS ★929](filamentgroup/criticalcss) - by FilamentGroup finds & outputs critical CSS


## Server-side modules

* [mod_pagespeed ★371](pagespeed/mod_pagespeed) - Apache module for automatic PageSpeed optimization
* [ngx_pagespeed ★3446](pagespeed/ngx_pagespeed) - Nginx module for automatic PageSpeed optimization

## Grunt tasks

* [grunt-penthouse ★69](fatso83/grunt-penthouse)
* [grunt-critical-css ★539](filamentgroup/grunt-criticalcss)
* [grunt-critical ★105](bezoerb/grunt-critical)

## CasperJS

* [critical-css-casperjs ★69 ⏳3Y](ibrennan/critical-css-casperjs) - CasperJS script to pull critical CSS information from pages

## PhantomJS

* [dr-css-inliner ★71 ⏳2Y](drdk/dr-css-inliner) - PhantomJS script to inline above-the-fold CSS on a page.

## Inline sources (styles, scripts)

* [inline-styles ★22 ⏳2Y](maxogden/inline-styles) - by Max Ogden, replaces `<link>` tags with inline `<style>` tags + inlines CSS url() calls with data URIs
* [gulp-inline-source ★153](fmal/gulp-inline-source) - by Filip Malinowski, replaces `<link>` tags with inline `<style>` tags, and replaces `<script src="">` tags with their inline content
* [inline-critical ★48](bezoerb/inline-critical) - by Ben Zörb, inline critical path CSS and load existing stylesheets with `loadCSS`
* [isomorphic-style-loader](https://github.com/kriasoft/isomorphic-style-loader/) for Webpack - allows to extract critical CSS for any given page/screen in React apps and inline it into HTML during server-side rendering (SSR). See [React Starter Kit ★14095](kriasoft/react-starter-kit) as an example.

## Async load CSS

Async loading should be used to fetch the rest of your site-wide styles after you've inlined your critical-path CSS.

* [loadCSS ★4293](filamentgroup/loadCSS) - loads CSS asynchronously using JS. [Research](https://gist.github.com/scottjehl/87176715419617ae6994) that led to this is also available.
* [async & conditional loading](https://gist.github.com/matt-bailey/602b40c77a5d3381ff26) - POC script for loading CSS files asynchronously and conditionally based on body tag classes
* [asyncLoader ★0 ⏳2Y](n0mad01/asyncLoader) - async script/stylesheet loader
* [basket.js](http://addyosmani.github.io/basket.js/) - async script/resource loader with support for localStorage caching. Can be [extended ★21 ⏳3Y](andrewwakeling/basket-css-example) to load stylesheets.

Note: The Guardian currently also cache their global styles into localStorage for subsequent page loads. More info in this [comment](https://gist.github.com/scottjehl/87176715419617ae6994).

## Online tools

* [Penthouse online](https://jonassebastianohlsson.com/criticalpathcssgenerator/)

## Bookmarklets/Extensions

* [Snippet](https://gist.github.com/PaulKinlan/6284142) by Paul Kinlan. Patrick Hamann has an [exercise](http://patrickhamann.com/workshops/performance/tasks/2_Critical_Path/2_2.html) using the snippet you can try out.
* [Snippet](https://gist.github.com/scottjehl/b6129da04733e4e0f9a4) by Scott Jehl
* [CSSVacuum ★37 ⏳3Y](ndreckshage/CSSVacuum) by ndreckshage

## Render-blocking issues detection

* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Online tool that measures the performance of a page for mobile devices and desktop devices. It fetches the url twice, once with a mobile user-agent, and once with a desktop-user agent. 
* [PSI](https://github.com/addyosmani/psi) - Node module for PageSpeed Insights reporting as part of your build process. Use directly with Gulp or use [grunt-pagespeed ★479](jrcryer/grunt-pagespeed) if a Grunt user. For local testing, a write-up using this task and [ngrok](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/) is available.
* [PageSpeed Insights DevTools extension](https://chrome.google.com/webstore/detail/pagespeed-insights-by-goo/gplegfbjlmmehdoakndmohflojccocli?hl=en) - Chrome extension for running PageSpeed tests from inside the browser.
* [PageSpeed Insights Checker for mobile extension](https://chrome.google.com/webstore/detail/pagespeed-insights-checke/mkjmodmicmpjedhoekkmafdgpocdkbna?hl=en) - checks Mobile PageSpeed score for every page and gives you a handy preview.

## Supplementary tools

* [UnCSS](https://github.com/giakki/uncss) removes unused CSS from pages, allowing you to reduce the global CSS you may need to load in for your site. Tasks are available for [Grunt](https://github.com/addyosmani/grunt-uncss), [Gulp ★947](ben-eb/gulp-uncss) and [other](https://addyosmani.com/blog/removing-unused-css/) build tools.

---
<p align="center">
	This list is a copy of <a href="addyosmani/critical-path-css-tools">addyosmani/critical-path-css-tools</a> with ranks
</p>
