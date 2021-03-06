<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="jondot/awesome-devenv">jondot/awesome-devenv</a> with ranks
</p>
---
# Awesome Dev Env [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

A curated list of awesome tools, resources and workflow tips making an awesome development environment.

Inspired by [awesome-go](https://github.com/avelino/awesome-go), which was in turn inspired by [awesome-python ★34408](vinta/awesome-python).

### Contributing

[Guidelines](https://github.com/jondot/awesome-devenv/blob/master/CONTRIBUTING.md) tweaked and adapted from `awesome-go` - thanks!

But in short:

* List is alphabetically sorted
* If you think an item shouldn't be here [open an issue](https://github.com/jondot/awesome-devenv/issues/new)


Many thanks to everyone on the [contributor list](https://github.com/jondot/awesome-devenv/graphs/contributors) :)


# Content

_Note: for an OS specific tool, please do your best to mark with `OSX/WIN/*NIX/LIN`_



- [Admins](#admins)
- [Benchmarking](#benchmarking)
- [Data](#data)
- [Diagnostics](#diagnostics)
- [Desktop](#desktop)
- [Dotfiles](#dotfiles)
- [Editors](#editors)
  - [Atom](#atom)
  - [Sublime Text](#sublime-text-3)
  - [Vim](#vim)
  - [IntelliJ](#intellij)
- [Git](#git)
- [Notifications](#notifications)
- [Orchestration](#orchestration)
- [Presentation](#presentation)
- [Shell](#shell)
- [Text](#text)
- [Terminal](#terminal)
- [Workflow](#workflow)


## Admins
*Tools to manage databases, permissions, etc.*

* [MongoHub](https://github.com/fotonauts/MongoHub-Mac/releases) - Native OSx client for mongo
* [Robomongo](http://robomongo.org/) - a cross platform Admin for MongoDB


## Benchmarking
*Tools to benchmark your code or services*

* [apachebench (ab)](http://httpd.apache.org/docs/2.2/programs/ab.html)
* [boom ★4778](rakyll/boom)
* [httperf](http://www.hpl.hp.com/research/linux/httperf/)
* [phantomas ★1987](macbre/phantomas) - website perf evaluation tool
* [siege](http://www.joedog.org/siege-home/)
* [Vegeta ★5696](tsenart/vegeta)
* [wrk ★12308](wg/wrk)
* [redis-faina](https://github.com/Instagram/redis-faina) Instagram's Redis counter/timing stats based on the MONITOR command


## Data
*Tools for handling online and offline data*

* [s3cmd ★2247](s3tools/s3cmd) - the S3 CLI tool for Amazon


## Diagnostics
*Tools for checking diagnosing your system while you work*

* [glances ★7387](nicolargo/glances)
* [nmon](http://nmon.sourceforge.net/pmwiki.php)


## Desktop
*Tools for improving and hacking around with your vanilla desktop*

* [Alfred](http://www.alfredapp.com/) - OSX productivity app `/OSX/`
* [hydra](https://github.com/sdegutis/hydra) - script your desktop
  `/OSX/`
* [Keycastr ★151](sdeken/keycastr) - show your keys while
  presenting/casting `/OSX/`


## Dotfiles

* [dotfiles.github.io](https://dotfiles.github.io/) - Collected dotfile resources. Has sections with dotfile bootstraps and lists of frameworks for various shells and editors.
* [Zach Holman's ★4476](holman/dotfiles) - oh-my-zsh, osx, Zsh, vi, Ruby, Git, and more
* [Mathias Bynens's ★16772](mathiasbynens/dotfiles) - .files, including ~/.osx — sensible hacker defaults for OS X
* [Thoughtbot's ★4202](thoughtbot/dotfiles) - A set of vim, zsh, git, and tmux configuration files
* [Paul Miller's ★671](paulmillr/dotfiles) - Colourful & robust OS X configuration files and utilities


## Editors
*Only awesome tools and addons for your favorite editor*

### Atom

* [atom-beautify ★977](Glavin001/atom-beautify) - Beautify HTML (including Handlebars), CSS (including Sass and Less), JavaScript, and much more in Atom.
* [file-icons](https://github.com/DanBrooker/file-icons) - Adds file specific icons to atom for improved visual grepping.
* [highlight-selected ★171](richrace/highlight-selected) - Double click on a word to highlight it throughout the open file.
* [minimap ★492](atom-minimap/minimap) - A graphical map (preview) of the full source code.
* [minimap-git-diff ★13](atom-minimap/minimap-git-diff) - A minimap binding for the Atom git-diff package.
* [minimap-highlight-selected ★28](atom-minimap/minimap-highlight-selected) - A minimap binding for the highlight-selected package.
* [atom-project-manager ★429](danielbrodin/atom-project-manager) - Get easy access to all your projects and manage them with project specific settings and options.
* [atom-tree-view-git-status ★14](subesokun/atom-tree-view-git-status) - Show the Git repository status in the Atom tree-view.
* [atom-pigments ★406](abe33/atom-pigments) - An Atom package to display colors in project and files.

### Vim

* [Powerline](https://github.com/Lokaltog/powerline) - improved status bar for your buffers.
* [snipmate ★1520](garbas/vim-snipmate) - textual snippets compatiable with Textmate snippets.
* [The Ultimate Vim Distribution](http://vim.spf13.com/) - spf13-vim is a distribution of vim plugins and resources for Vim, GVim and MacVim.

### Sublime Text 3

* [AdvancedNewFile ★680](skuroda/Sublime-AdvancedNewFile) - File creation plugin.
* [Emmet ★4876](sergeche/emmet-sublime)
* [Git Gutter ★3463](jisaacks/GitGutter) - display changed/added lines in the margin of the editor window.
* [jsFormat ★1267](jdc0589/JsFormat) - Javascript formatting.
* [LiveReload](https://github.com/dz0ny/LiveReload-sublimetext2) - LiveReload plugin.
* [MarkdownEditing ★2006](SublimeText-Markdown/MarkdownEditing) - Markdown syntax understanding and good color schemes.
* [Package Control](https://sublime.wbond.net/installation) - The Sublime Text package manager.
* [RubyTest ★748 ⏳2Y](maltize/sublime-text-2-ruby-tests) - Plugin for running Ruby tests.
* [Side Bar Enhancments ★66](titoBouzout/SideBarEnhancements) - Enhancements to Sublime Text sidebar. Files and folders.
* [Sublime Git ★2652](kemayo/sublime-text-git) - Git Integration for Sublime.
* [Sublime Linter ★1290](SublimeLinter/SublimeLinter3) - Interactive code linting.
* [TrailingSpaces ★785](SublimeText/TrailingSpaces) - Highlight trailing spaces and delete them in a flash.

### Intellij

* [keymap ★7 ⏳2Y](jondot/keymaps) - a hybrid Vim/ReSharper/Intellij keymap


## Git
*Tools and addons for making an awesome Git experience*

* [awesome-github ★151 ⏳1Y](fffaraz/awesome-github) - Faraz Fallahi maintains a curated list of GitHub & Git resources.
* [gh ★739 ⏳2Y](jingweno/gh) - Fast GitHub command line client (hub port to Go)
* [git-extra-commands ★162](unixorn/git-extra-commands) - collected git helper scripts
* [git-extras](https://github.com/visionmedia/git-extras) - GIT utilities -- repo summary, repl, changelog population, author commit percentages and more
* [git-it-on ★39](peterhurford/git-it-on.zsh) - ZSH plugin, adds a gitit command that opens the current directory on github in your current branch
* [git-semver ★109](markchalloner/git-semver) - A git plugin to make Semantic Versioning 2.0.0 and Change Log management easier.
* [git-sweep ★1597](arc90/git-sweep) - safely removes branches that have been merged into the master
* [git-up ★2740](aanand/git-up) - a better 'git pull'
* [hub](https://hub.github.com/) - git CLI wrapper which makes working with GitHub easier
* [scm_breeze](https://github.com/ndbroadbent/scm_breeze) Streamline your git workflow
* [tig](http://jonas.nitro.dk/tig/) - an ncurses-based text-mode interface for git

## Notifications
*Tools that notify developers about changes in their work environment*

* [CatLight](https://catlight.io) - status notifier for developers. Checks the status of continuous delivery builds and shows desktop notifications.

## Orchestration
*Tools for orchestrating awesome development environments*

* [azk ★788](azukiapp/azk) - a lightweight open source engine to orchestrate development environments
* [Nanobox ★939](nanobox-io/nanobox) - A micro-PaaS (μPaaS) for creating consistent, isolated, development environments deployable anywhere https://nanobox.io.

## Presentation
*Tools for presenting your work*

* [bespoke.js](https://github.com/markdalgleish/bespoke.js) - DIY Presentation Micro-Framework
* [impress.js ★31610](impress/impress.js) - presentation framework based on the power of CSS3 transforms and transitions
* [remark ★6149](gnab/remark) - markdown based presentation on your browser
* [reveal.js ★34726](hakimel/reveal.js) - markdown based presentation on your browser
* [deck.js ★5138](imakewebthings/deck.js) - markdown based presentation on your browser
* [vimdeck ★1051](tybenz/vimdeck) - present inside your Vim
* [WebSlides](https://github.com/jlantunez/webslides) - Making HTML presentations easy

## Shell
*Tools for having an awesome shell environment*

* [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) - List of zsh plugins usable with [zgen](https://github.com/tarjoilija/zgen) and other [oh-my-zsh ★54129](robbyrussell/oh-my-zsh) compatible zsh frameworks
* [fish-shell ★7691](fish-shell/fish-shell) - The user-friendly command line shell
* [oh-my-fish ★2253](oh-my-fish/oh-my-fish) - Framework for managing your fish shell configuration inspired by oh-my-zsh.
* [oh-my-zsh ★54129](robbyrussell/oh-my-zsh) - A community driven framework for managing zsh configuration.
* [zgen ★747](tarjoilija/zgen) - Faster framework for managing your zsh configuration, backward compatible with oh-my-zsh plugins
* [zsh](http://www.zsh.org/) - A shell designed for interactive use, although it is also a powerful scripting language.
* [shellcheck ★7758](koalaman/shellcheck) - Lint for shell. Will find deprecated and/or dangerous usage in shell scripts
* [zsh quickstart kit ★98](unixorn/zsh-quickstart-kit) - Quick intro for getting set up with zsh and zgen

## Text
*Tools for working with text files - search, replace, processing*

* [ack ★1211](petdance/ack2) - the Perl based
  better-than-grep tool.
* [ag ★12322](ggreer/the_silver_searcher) - A C based code-searching tool similar to ack, but faster
* [peco ★3922](peco/peco) - interactive filtering, like interactive Grep


## Terminal
*Tools and addons for terminal and terminal work*

* [autojump](https://github.com/joelthelion/autojump) - remembers your
  folders and jump to them based on partial recall (e.g. `j proj` will jump
to `/home/Users/yourself/projects`.
* [fasd ★3112](clvv/fasd) Command-line productivity booster, offers quick access to files and directories.
* [homebrew](http://brew.sh) - Makes it easy to install open source packages on an `OS X` system with a single command.
* [httpie](http://httpie.org/) A command line HTTP client, a user-friendly cURL replacement.
* [iTerm2](http://www.iterm2.com/) - a great terminal replacement `/OSX/`
* [jq](https://stedolan.github.io/jq/) - a lightweight and flexible command-line JSON processor
* [oh-my-zsh ★54129](robbyrussell/oh-my-zsh) - the
  incredible ZSH addon.
* [Pipe Viewer](http://www.ivarch.com/programs/pv.shtml) - a tool for monitoring the progress of data through a pipeline
* [tmux](https://tmux.github.io/) the awesome terminal multiplexer.


## Workflow
*Tools and addons which improve your daily workflow with code*

* [fswatch](https://github.com/alandipert/fswatch) - a watch tool which
  will emit FS events and you can run commands on demand with. Note -
`fswatch-run` too.
* [guard ★5345](guard/guard) - FS watch tool with a huge ecosystem of plugins
* [LiveReload](http://livereload.com/) - FS watch and preprocessor as a desktop app for `/OSX/` and `/WIN/` with complementary browser extensions
  * [guard-livereload ★1901](guard/guard-livereload) - Guard plugin compatible with LiveReload's browser extensions
* [watchman ★5475](facebook/watchman) - Facebook's better
  `watch` - note it works as a service.
* [Zappr ★257](zalando/zappr) - GitHub integration built to enhance your project workflow via enable/disable pull request approval checks.
---
<p align="center">
	This list is a copy of <a href="jondot/awesome-devenv">jondot/awesome-devenv</a> with ranks
</p>
