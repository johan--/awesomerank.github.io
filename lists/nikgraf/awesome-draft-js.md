<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="nikgraf/awesome-draft-js">nikgraf/awesome-draft-js</a> with ranks
</p>
---
# Awesome Draft.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

[Draft.js](https://facebook.github.io/draft-js/) is a framework for building rich text editors in React.

**Table of Contents**

- [Community ★804](nikgraf/awesome-draft-js#community)
- [Presentations ★804](nikgraf/awesome-draft-js#presentations)
- [Projects on Top of Draft.js ★804](nikgraf/awesome-draft-js#standalone-editors-built-on-draftjs)
- [Common Utilities ★804](nikgraf/awesome-draft-js#common-utilities)
- [Blog Posts & Articles ★804](nikgraf/awesome-draft-js#blog-posts--articles)
- [Live Demos ★804](nikgraf/awesome-draft-js#live-demos)
- [Usage in Production ★804](nikgraf/awesome-draft-js#usage-in-production)
- [License ★804](nikgraf/awesome-draft-js#license)

## Community

* [Slack channel](https://draftjs.herokuapp.com/)

## Presentations
* [Rich Text Editing with React @ React.js Conf 2016 by Isaac Salier-Hellendag ](https://www.youtube.com/watch?v=feUYwoLhE_4)
* [Rich text editing with Draft.js & DraftJS Plugins by Nik Graf](https://www.youtube.com/watch?v=gxNuHZXZMgs)
* [React Ep. 37: Draftjs by What I Learned Today – Atomic Jolt](https://www.youtube.com/watch?v=0k9suXgCtTA)
* [008 - Draft.js Plugins @ React30](https://www.youtube.com/watch?v=w-PqnpMizcQ)
* [Draft.js at HubSpot by Ben Briggs](http://product.hubspot.com/blog/tech-talk-at-night-react-meetup)
* [Draft.js under the hood - React Melbourne meetup](https://www.youtube.com/watch?feature=player_embedded&v=vOZAO3jFSHI)

## Standalone Editors Built on Draft.js

* [Draft WYSIWYG ★312](bkniffler/draft-wysiwyg) - WYSIWYG editor that with drag&drop, resizing & tooltips.
* [Draft.js Editor ★80](AlastairTaft/draft-js-editor) - A Rich text editor inspired by Medium & Facebook Notes.
* [React-RTE ★1234](sstur/react-rte) - A full-featured textarea replacement similar to CKEditor or TinyMCE.
* [Facebook Notes Clone(ish) ★177 ⏳1Y](andrewcoelho/react-text-editor) - Rich text editor similar to Facebook notes.
* [Megadraft ★358](globocom/megadraft) - A rich text editor with a nice default base of plugins and extensibility.
* [Medium Draft ★798](brijeshb42/medium-draft) - Medium-like rich text editor with a focus on keyboard shortcuts.
* [React-Draft-Wyiswyg](https://github.com/jpuri/react-draft-wysiwyg.git) - A WYISWYG editor, with various text editing options and corresponding HTML generation.
* [Dante 2 ★274](michelson/dante2) - Just another Medium clone built on top of DraftJs.
* [Last Draft ★92](vacenz/last-draft) - A Draft editor built with Draft.js plugins.

## Plugins and Decorators Built for Draft.js

* [Draft.js Plugins ★1984](draft-js-plugins/draft-js-plugins) - A Plugin architecture on top of Draft.js
  - [Emoji](https://www.draft-js-plugins.com/plugin/emoji) - Slack-like emoji support
  - [Stickers](https://www.draft-js-plugins.com/plugin/sticker) - Facebook-like sticker support
  - [Hashtags](https://www.draft-js-plugins.com/plugin/hashtag) - Twitter-like hashtag support
  - [Linkify](https://www.draft-js-plugins.com/plugin/linkify) - Automatically turn links into anchor-tags.
  - [Mentions](https://www.draft-js-plugins.com/plugin/mention) - Twitter-like mention support
  - [Undo](https://www.draft-js-plugins.com/plugin/undo) - Undo & Redo button.
  - [Counter](https://www.draft-js-plugins.com/plugin/counter) - Character, word & line counting.
  - [Autolist ★41](icelab/draft-js-autolist-plugin) - Automatic unordered/ordered list creation.
  - [Block Breakout ★21](icelab/draft-js-block-breakout-plugin) - Break out of block types as you type.
  - [Markdown Shortcuts ★68](ngs/draft-js-markdown-shortcuts-plugin) - Markdown syntax shortcuts.
  - [Single Line ★13](icelab/draft-js-single-line-plugin) - Restrict to a single line of input.
  - [RichButtons ★29](jasonphillips/draft-js-richbuttons-plugin) - Add and customize rich formatting buttons.
  - [Katex ★4](letranloc/draft-js-katex-plugin) - Insert and render LaTeX using Katex.
  - [Mathjax ★11](efloti/draft-js-mathjax-plugin) - Edit math using (La)TeX rendered by Mathjax.
  - [Buttons ★20](vacenz/last-draft-js-plugins)
  - [Color Picker ★20](vacenz/last-draft-js-plugins)
  - [Embed ★20](vacenz/last-draft-js-plugins)
  - [EmojiPicker ★20](vacenz/last-draft-js-plugins)
  - [GifPicker ★20](vacenz/last-draft-js-plugins)
  - [Link ★20](vacenz/last-draft-js-plugins)
  - [Modal ★20](vacenz/last-draft-js-plugins)
  - [Sidebar ★20](vacenz/last-draft-js-plugins)
  - [Toolbar ★20](vacenz/last-draft-js-plugins)
* [Draft.js Gutter](https://github.com/yepnamesjames/draft-js-gutter) - Compliments line number gutter.
* [Draft.js Basic HTML Editor ★61](dburrows/draft-js-basic-html-editor) - Accept html as its input format, and return html to an onChange.
* [Draft.js Prism](https://github.com/SamyPesse/draftjs-prism)- Highlight code blocks using Prism.
* [Draft.js Typeahead ★81](dooly-ai/draft-js-typeahead) - Support for typeahead functionality.
* [Draft Extend ★39](HubSpot/draft-extend) - Build extensible Draft.js editors with configurable plugins and integrated serialization.

## Common Utilities

* [BackDraft.js ★35 ⏳1Y](evanc/backdraft-js) - Function to turn a rawContentBlock into a marked-up string.
* [Draft.js Exporter ★24](rkpasia/draft-js-exporter) - Export and format the content from Draft.js.
* [Draft.js: Export ContentState to HTML ★284](sstur/draft-js-export-html) - Export ContentState to HTML.
* [Redraft ★52](lokiuz/redraft) - Renders the result of Draft.js convertToRaw using provided callbacks, works well with React
* [Draft.js exporter (Ruby) ★4](ignitionworks/draftjs_exporter) - Export Draft.js content state into HTML.
* [Draft.js exporter (Python) ★14](springload/draftjs_exporter) - Library to convert Draft.js raw ContentState to HTML
* [Draft.js AST Exporter ★19](icelab/draft-js-ast-exporter) - Export content into an abstract syntax tree (AST).
* [Draft.js AST Importer ★3](icelab/draft-js-ast-importer)- Emport an abstract syntax tree (AST) output from the companion draft-js-ast-exporter.
* [Draft.js Multidecorators](https://github.com/SamyPesse/draftjs-multidecorators) - Combine multiple decorators.
* [Draft.js SimpleDecorator ★12](Soreine/draft-js-simpledecorator) - Easily create flexible decorators.
* [DraftJS Utils](https://github.com/jpuri/draftjs-utils.git) - Set of utility functions for DraftJS.
* [DraftJs to HTML](https://github.com/jpuri/draftjs-to-html.git) - Library for generating HTML for DraftJS editor content.
* [Draft Convert ★128](HubSpot/draft-convert) - Extensibly serialize & deserialize Draft.js ContentState with HTML.
* [HTML to DraftJS ★20](jpuri/html-to-draftjs) - Convert plain HTML to DraftJS Editor content.
* [Draft.js Exporter (Go) ★10](ejilay/draftjs) - Export Draft.js content state into HTML.
* [React Native Draft.js Render ★93](globocom/react-native-draftjs-render) - A React Native render for Draft.js model.

## Blog Posts & Articles

* [Facebook open sources rich text editor framework Draft.js](https://code.facebook.com/posts/1684092755205505/facebook-open-sources-rich-text-editor-framework-draft-js/)
* [This Blog Post Was Written Using Draft.js](https://dev.to/ben/this-blog-post-was-written-using-draftjs)
* [How Draft.js Represents Rich Text Data](https://medium.com/@rajaraodv/how-draft-js-represents-rich-text-data-eeabb5f25cf2#.7gd8psdvi)
* [A Beginner’s Guide to Draft.js](https://medium.com/@adrianli/a-beginner-s-guide-to-draft-js-d1823f58d8cc#.uufeulpl5)
* [Implementing todo list in Draft.js](http://bitwiser.in/2016/08/31/implementing-todo-list-in-draft-js.html)
* [Draft.js Pieces](https://cannibalcoder.com/2016/12/02/draft-js-pieces/)

## Live Demos

* [REACTing Codepen Comment Editor - Draft.js](http://codepen.io/rkpasia/full/jqbrpq)
* [Draft.js Examples - A Heroku app w/ several example Draft.js Editors from different projects](http://draftjs-examples.herokuapp.com/)
* [Draft-js Samples - An app with examples and code explanations ★11](Mair/react-meetup-draftjs)

## Playgrounds for Examples from Official Repository (v.0.10.0)
* [Rich Text Editor](http://codepen.io/Kiwka/pen/YNYvyG)
* [Color Editor](http://codepen.io/Kiwka/pen/oBpVve)
* [Convert from HTML Editor](http://codepen.io/Kiwka/pen/YNYgWa)
* [Entity Editor](http://codepen.io/Kiwka/pen/wgpOoZ)
* [Link Editor](http://codepen.io/Kiwka/pen/ZLvPeO)
* [Media Editor](http://codepen.io/Kiwka/pen/rjpRzj)
* [Plain Text Editor](http://codepen.io/Kiwka/pen/jyYJzb)
* [Decorators Editor - Tweet example](http://codepen.io/Kiwka/pen/KaZERV)

## Usage in Production
* [Small Teaser](https://www.smallteaser.com/articles/write)
* [HKW Technosphere Magazine](http://technosphere-magazine.hkw.de/)
* [Douban Read](https://read.douban.com/editor_ng)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nikolaus Graf](https://github.com/nikgraf/) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="nikgraf/awesome-draft-js">nikgraf/awesome-draft-js</a> with ranks
</p>
