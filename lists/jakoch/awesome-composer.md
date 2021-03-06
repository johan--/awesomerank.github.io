<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="jakoch/awesome-composer">jakoch/awesome-composer</a> with ranks
</p>
---
## Awesome Composer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome) [![Build Status](https://api.travis-ci.org/jakoch/awesome-composer.svg?branch=master)](https://travis-ci.org/jakoch/awesome-composer) [![license](https://img.shields.io/github/license/jakoch/awesome-composer.svg?maxAge=2592000)]()

[<img src="https://raw.githubusercontent.com/jakoch/awesome-composer/master/logo-composer-transparent.png" align="right" width="150">](https://getcomposer.org/)

> A curated list of resources for Composer, Packagist, Satis, Plugins, Scripts, Videos, Tutorials.

You might also like [awesome-php ★15483](ziadoz/awesome-php).

*Please read the [contribution guidelines](https://github.com/jakoch/awesome-composer/blob/master/contributing.md) before contributing.*

## Composer

- [Official Website](https://getcomposer.org/)
- [Issues](https://github.com/composer/composer/issues)
- [Github ★9458](composer/composer)
- [Getting Started Guide and Installation Instructions](https://getcomposer.org/doc/00-intro.md)
- [Documentation](https://getcomposer.org/doc/)
- [API Documentation](https://getcomposer.org/apidoc/master/index.html)
- [Find Packages on Packagist](https://packagist.org/)
- [CheatSheet](http://composer.json.jolicode.com/) - Overview of CLI commands and `composer.json` schema.
- [Composer Installers ★675](composer/installers) - Composer installers for multiple frameworks.

### Support

#### Stack Overflow

- You might use the following tags: `composer-php`, `packagist`, `satis` + `php`.
- [Ask a new question](http://stackoverflow.com/questions/ask?tags=composer-php+php)
- [Find questions tagged `composer-php`](http://stackoverflow.com/questions/tagged/composer-php)

#### IRC

- IRC channels are on `irc.freenode.org`: [#composer](https://webchat.freenode.net/?channels=composer) for users and [#composer-dev](https://webchat.freenode.net/?channels=composer-dev) for development.

## Plugins

- [Documentation for Plugins](https://getcomposer.org/doc/articles/plugins.md) - This offical documentation is good starting point, when writing a Composer plugin.
- [Composer-Asset-Plugin ★724](fxpio/composer-asset-plugin) - A npm/Bower Dependencies Manager for Composer.
- [Composer-AWS ★44](naderman/composer-aws) - The plugin loads repository data and downloads packages from Amazon S3 (with authentication support for private repositories).
- [Composer-Composition ★102 ⏳1Y](bamarni/composition) - Provides an API, for checking your environment at runtime.
- [Composer-Suggest ★2](nfreear/composer-suggest) - Enables you to install a custom group of suggested packages, based on keyword patterns.
- [Composer-Versions-Check ★112](Soullivaneuh/composer-versions-check) - Shows outdated packages from last major versions after using the update command (showing "Latest is vX.Y.Z").
- [Composer-Changelogs ★368](pyrech/composer-changelogs) - Provides a summary of the updates with links to changelog/releasenote/tag. The output is ready to be pasted into the commit message when updating the composer.lock file.
- [Composer-Merge-Plugin ★257](wikimedia/composer-merge-plugin) - Merges multiple `composer.json` files at Composer runtime.
- [Composer-Bin-Plugin ★36](bamarni/composer-bin-plugin) - Adds support for managing dependencies for multiple packages in a single repository or isolate bin dependencies.
- [Composer-Inheritance-Plugin ★3](theofidry/composer-inheritance-plugin) - Opinionated version of Wikimedia composer-merge-plugin to work in pair with Bamarni composer-bin-plugin.
- [Composer-MonoRepo-Plugin ★158](beberlei/composer-monorepo-plugin) - The plugin adds support for managing dependencies for multiple packages in a single repository.
- [Composer-Patches-Plugin ★52](netresearch/composer-patches-plugin) - Enables you to provide patches for any package from any package. When the dependency is fetched, the patch is applied on top.
- [Composer-Patches ★241](cweagans/composer-patches) - The plugin applies a patch from a local or remote file to any required package.
- [Composer-Cleanup-Plugin ★54 ⏳1Y](barryvdh/composer-cleanup-plugin) - Removes tests & documentation folders from the vendor dir.
- [Composer-Cleaner ★35](dg/composer-cleaner) - The tool removes unnecessary files and directories from the vendor directory.
- [Composer-Shared-Package-Plugin ★146](Letudiant/composer-shared-package-plugin) - Allows you to share your selected packages between your projects by creating symlinks.
- [Composer-Symlinker ★9](dg/composer-symlinker) - Enables you to load some packages from different directories (instead of loading them from /vendor).
- [Prestissimo ★2698](hirak/prestissimo) - A parallel downloader using `phpext_curl`.
- [Composer-FastFetch ★5 ⏳1Y](jakoch/composer-fastfetch) - Parallel Downloader using external download tools: Aria2.
- [Composer-Curl-Plugin ★2 ⏳1Y](ngyuki/composer-curl-plugin) - The plugin use phpext_curl for downloading packages.
- [Composer-Custom-Directory-Installer ★78](mnsami/composer-custom-directory-installer) - A composer plugin, to install different types of composer packages in custom directories outside the default composer installation path (which is in the vendor folder).
- [Composer-Dependency-Analyzer](https://packagist.org/packages/jms/composer-deps-analyzer) - Allows you to build a dependency graph for an installed composer project.
- [PackageVersions ★117](Ocramius/PackageVersions) - Provides a very quick and easy access to installed composer dependency versions.
- [Composer Locator ★47](mindplay-dk/composer-locator) - Provides a means of locating the installation path for a given Composer package name.  
- [PackageInfo ★0](ThaDafinser/PackageInfo) - Check if a package is installed and retrieve all package informations like version, tag release date, description, ... 
- [composer-ignore-plugin ★3](lichunqiang/composer-ignore-plugin) - The composer plugin to remove useless files in vendor by yourself.
- [composer-git-hooks ★118](BrainMaestro/composer-git-hooks) - A library for easily managing git hooks in your composer config.
- [Symfony-Flex](https://github.com/symfony/flex) - Provides [recipe-based ★193](symfony/recipes) installation and configuration management for Symfony packages.
- [phpcodesniffer-composer-installer ★15](DealerDirect/phpcodesniffer-composer-installer) - Automates the configuration of custom PHP_CodeSniffer standards/sniffs via Composer

## Tools

- [Composer SemVer Checker](https://semver.mwl.be) - Enables you identify constraint to version resolution issues, by doing a semantic version check for Packagist hosted packages.
- [Composer-Yaml ★46](igorw/composer-yaml) - This tool converts composer.yml to composer.json.
- [Studio ★601](franzliedke/studio) - A workbench for developing Composer packages. Its an alternative to editing dependencies in the vendor folder or using [PathRepositories](https://getcomposer.org/doc/05-repositories.md#path) to load a local clone of your dependency into your project.
- [OctoLinker Browser Extension ★2149](OctoLinker/browser-extension) - Enables you to navigate Composer/NPM dependencies on Github.
- [ComposerRequireChecker ★23](maglnet/ComposerRequireChecker) - A CLI tool to analyze dependencies and verify that no unknown imported symbols are used in the sources of a package.

## Scripts

- [composer-travis-lint ★1](raphaelstolt/composer-travis-lint) - Allows you to lint the Travis CI configuration file (`.travis.yml`).
- [composer-multitest ★3](raphaelstolt/composer-multitest) - Enables you to run a Composer script against multiple, locally installed PHP versions, which are managed by PHPBrew or phpenv.
- [ScriptsDev ★35](neronmoon/scriptsdev) - Enables you to use a `scripts-dev` section, which triggers scripts only in dev mode.
- [ParameterHandler ★335](Incenteev/ParameterHandler) - Allows you to manage your ignored parameters when running a composer install or update.
- [PhantomJS-Installer ★103](jakoch/phantomjs-installer)- A Composer Package which installs the PhantomJS binary (Linux, Windows, Mac) into /bin of your project.
- [tooly ★53](tommy-muehle/tooly-composer-script) - Manage needed PHAR files in your project composer.json. Every PHAR file will be saved in the composer binary directory. Optional with GPG verification for every PHAR.

## Packagist-compatible repositories

- [WordPress Packagist](https://wpackagist.org/) - Mirrors the WordPress plugin and theme directories as a Composer repository.
- [Asset Packagist](https://asset-packagist.org/) - Enables installation of Bower and NPM packages as native Composer packages.

## Tutorials 

- [A beginners guide to Composer](https://scotch.io/tutorials/a-beginners-guide-to-composer)
- [A short & simple Composer tutorial](https://www.dev-metal.com/composer-tutorial/)
- [Easy package management with Composer](https://code.tutsplus.com/tutorials/easy-package-management-with-composer--net-25530)
- [PHP Dependency Management with Composer](https://www.sitepoint.com/php-dependency-management-with-composer/)
- [Composer Primer](https://daylerees.com/composer-primer/)
- [PHP Composer Magento Tutorial by Alan Storm](http://alanstorm.com/php_composer_magento_tutorial/)

## Slides

- Slides by Nils Aderman
  - [Composer Update](http://www.naderman.de/slippy/src/?file=2015-02-03-Composer-Update.html)
  - [Dependency Management with Composer PHP Reinvented](http://www.naderman.de/slippy/src/?file=2015-02-01-Dependency-Management-with-Composer-PHP-Reinvented.html)
  - [PHP Reinvented - How Composer helped shape the new way of writing PHP](http://www.naderman.de/slippy/src/?file=2014-04-13-PHP-Reinvented.html)
- Slides by Jordi Boggiano
  - [Composer Best Practices](http://slides.seld.be/?file=2015-07-25+Composer+Best+Practices.html)
  - [Introduction to Composer](http://slides.seld.be/?file=2015-06-30+Introduction+to+Composer.html)
  - [In Depth with Composer](http://slides.seld.be/?file=2013-10-05+In-Depth+with+Composer.html)
  - [Dependency Management with Composer](http://slides.seld.be/?file=2013-10-04+Dependency+Management+with+Composer.html)

## Books

- [Creating and Using Composer Packages](https://www.packtpub.com/books/content/creating-and-using-composer-packages)

## Blogs

- [Jordi Boggiano (seldaek)](https://seld.be/)
- [Nils Adermann (naderman)](http://naderman.de/)
- [Composer: Part 1 - What & Why](http://blog.nelm.io/2011/12/composer-part-1-what-why/)
- [Composer: Part 2 - Impact](http://blog.nelm.io/2011/12/composer-part-2-impact/)
- [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html)
- [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html)

## Videos

- [Composer Best Practices — Jordi Boggiano @ php[tek] 2015](https://www.youtube.com/watch?v=uNlYpSTiAcA)
- [Wonderful World of Composer](https://knpuniversity.com/screencast/composer) 
- [PHP Composer Quickstart](https://www.youtube.com/watch?v=Ejr4Xqs9V2I)
- [How Composer helped shape the new way of writing PHP - Nils Adermann @ Drupal Camp Frankfurt](https://www.youtube.com/watch?v=C2jfLM-Egvg)
- [Composer Package Management - Nils Adermann @ T3CON12DE](https://www.youtube.com/watch?v=P4Qnp90TG0g)

## Packagist

- [Packagist-Crawler ★25](hirak/packagist-crawler) - Script to mirror Packagist metadata.

### Packagist Mirrors

- Europe
  - France https://packagist.org/ - 87.98.253.214 (ovh.net).
- Asia
  - Japan http://packagist.jp/ - 104.28.30.100 (CloudFlare, San Fransico, USA).
  - China http://packagist.cn/ - 123.56.107.40 (Aliyun Computing; Alibaba, Hangzhou, China). (Abandoned)
  - China http://www.phpcomposer.com/
- USA
  - Give http://packagist.jp/ a try.

## Composer Repositories

### Private Packagist
- [Private Packagist Cloud](https://packagist.com) - A Composer Repository as a Service for private packages and to mirror packages from other repositories
- [Private Packagist Enterprise](https://packagist.com) - On-premise self-hosted version of Private Packagist

### Satis

- [Gitlab-Composer ★109](wemakecustom/gitlab-composer) - This is a branch/tag indexer for Gitlab repositories.
- [Satisfy ★164](ludofleury/satisfy) - Satis composer repository manager with a Web UI.
- [Satis Control Panel ★56](realshadow/satis-control-panel) - A simple web UI for managing your Satis Repository with optional CI integration.
- [Satis Go ★37](benschw/satis-go) - A web server for managing Satis configuration and hosting the generated Composer repository.

### Toran Proxy

- [ToranProxy](https://toranproxy.com/) (deprecated) - In addition to providing a composer repository ToranProxy acts as a proxy server for Packagist and GitHub.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jens A. Koch](https://github.com/jakoch) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="jakoch/awesome-composer">jakoch/awesome-composer</a> with ranks
</p>
