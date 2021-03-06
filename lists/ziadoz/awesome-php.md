<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="ziadoz/awesome-php">ziadoz/awesome-php</a> with ranks
</p>
---
# Awesome PHP [![Build Status](https://api.travis-ci.org/ziadoz/awesome-php.svg?branch=master)](https://travis-ci.org/ziadoz/awesome-php)

A curated list of amazingly awesome PHP libraries, resources and shiny things.

## Contributing
Please see [CONTRIBUTING](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md) and [CODE-OF-CONDUCT](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) for details.

## Table of Contents
- [Awesome PHP](#awesome-php)
    - [Composer Repositories](#composer-repositories)
    - [Dependency Management](#dependency-management)
    - [Dependency Management Extras](#dependency-management-extras)
    - [Frameworks](#frameworks)
    - [Framework Extras](#framework-extras)
    - [Components](#components)
    - [Micro Frameworks](#micro-frameworks)
    - [Micro Framework Extras](#micro-framework-extras)
    - [Routers](#routers)
    - [Templating](#templating)
    - [Static Site Generators](#static-site-generators)
    - [HTTP](#http)
    - [Middlewares](#middlewares)
    - [URL](#url)
    - [Email](#email)
    - [Files](#files)
    - [Streams](#streams)
    - [Dependency Injection](#dependency-injection)
    - [Imagery](#imagery)
    - [Testing](#testing)
    - [Continuous Integration](#continuous-integration)
    - [Documentation](#documentation)
    - [Security](#security)
    - [Passwords](#passwords)
    - [Code Analysis](#code-analysis)
    - [Architectural](#architectural)
    - [Debugging and Profiling](#debugging-and-profiling)
    - [Build Tools](#build-tools)
    - [Task Runners](#task-runners)
    - [Navigation](#navigation)
    - [Asset Management](#asset-management)
    - [Geolocation](#geolocation)
    - [Date and Time](#date-and-time)
    - [Event](#event)
    - [Logging](#logging)
    - [E-commerce](#e-commerce)
    - [PDF](#pdf)
    - [Office](#office)
    - [Database](#database)
    - [Migrations](#migrations)
    - [NoSQL](#nosql)
    - [Queue](#queue)
    - [Search](#search)
    - [Command Line](#command-line)
    - [Authentication and Authorization](#authentication-and-authorization)
    - [Markup](#markup)
    - [Strings](#strings)
    - [Numbers](#numbers)
    - [Filtering and Validation](#filtering-and-validation)
    - [API](#api)
    - [Caching](#caching)
    - [Data Structure and Storage](#data-structure-and-storage)
    - [Notifications](#notifications)
    - [Deployment](#deployment)
    - [Internationalisation and Localisation](#internationalisation-and-localisation)
    - [Third Party APIs](#third-party-apis)
    - [Extensions](#extensions)
    - [Miscellaneous](#miscellaneous)
- [Software](#software)
    - [PHP Installation](#php-installation)
    - [Development Environment](#development-environment)
    - [Virtual Machines](#virtual-machines)
    - [Integrated Development Environment](#integrated-development-environment)
    - [Web Applications](#web-applications)
    - [Infrastructure](#infrastructure)
- [Resources](#resources)
    - [PHP Websites](#php-websites)
    - [Other Websites](#other-websites)
    - [PHP Books](#php-books)
    - [PHP Videos](#php-videos)
    - [PHP Podcasts](#php-podcasts)
    - [PHP Reading](#php-reading)
    - [PHP Internals Reading](#php-internals-reading)
- [Contributing](#contributing)

## Composer Repositories
*Composer Repositories.*

* [Firegento](http://packages.firegento.com/) - Magento Module Composer Repository.
* [Packagist](https://packagist.org/) - The PHP Package Repository.
* [PaketHub](https://pakethub.com/) - All-in-One PHP Package Repository.
* [Private Packagist](https://packagist.com/) - Composer package archive as a service for PHP.
* [WordPress Packagist](https://wpackagist.org/) - Manage your plugins with Composer.

## Dependency Management
*Libraries for dependency and package management.*

* [Composer Installers ★675](composer/installers) - A  multi framework Composer library installer.
* [Composer](https://getcomposer.org/) - A package and dependency manager.
* [Melody](http://melody.sensiolabs.org/) - A tool to build one file Composer scripts.
* [Pickle ★973](FriendsOfPHP/pickle) - A PHP extension installer.

## Dependency Management Extras
*Extras related to dependency management.*

* [Composed ★25](joshdifabio/composed) - A library to parse your project's Composer environment at runtime.
* [Composer Checker ★12 ⏳2Y](silpion/composer-checker) - A tool to validate Composer configurations.
* [Composer Merge Plugin ★257](wikimedia/composer-merge-plugin) - A composer plugin to merge several composer.json files.
* [Composition ★102 ⏳1Y](bamarni/composition) - A library to check your Composer environment at runtime.
* [NameSpacer ★59 ⏳4Y](ralphschindler/Namespacer) - A library to convert from underscores to namespaces.
* [Patch Installer ★50 ⏳4Y](goatherd/patch-installer) - A library to install patches using Composer.
* [Prestissimo ★2698](hirak/prestissimo) - A composer plugin which enables parallel install process.
* [Satis ★1421](composer/satis) - A static Composer repository generator.
* [tooly ★53](tommy-muehle/tooly-composer-script) - A library to manage PHAR files in project using Composer.
* [Toran Proxy](https://toranproxy.com) - A static Composer repository and proxy.

## Frameworks
*Web development frameworks.*

* [Aura Framework](http://auraphp.com/framework/) - A framework built from independent components.
* [CakePHP](https://cakephp.org/) - A rapid application development framework (CP).
* [Laravel 5](https://laravel.com/) - Another PHP framework (L5).
* [Nette](https://nette.org) - Another framework comprised of individual components.
* [Phalcon](https://phalconphp.com/en/) - A framework implemented as a C extension.
* [PPI Framework 2](http://www.ppi.io) - An interoperability framework.
* [Symfony](https://symfony.com/) - A framework comprised of individual components (SF).
* [Yii2 ★10222](yiisoft/yii2) - Another PHP framework.
* [Zend Framework 2](https://framework.zend.com) - Another framework comprised of individual components (ZF2).
* [Ice](https://www.iceframework.org/) - Another simple and fast PHP framework delivered as C-extension.

## Framework Extras
*Extras related to web development frameworks.*

* [CakePHP CRUD ★266](friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP.
* [Knp RAD Bundle](http://rad.knplabs.com/) - A Rapid Application Development (RAD) bundle for Symfony.
* [Symfony CMF ★732](symfony-cmf/symfony-cmf) - A Content Management Framework to create custom CMS.

## Components
*Standalone components from web development frameworks and development groups.*

* [Aura](http://auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
* [CakePHP Plugins](https://plugins.cakephp.org/) - A directory of CakePHP plugins.
* [Hoa Project](https://hoa-project.net/En/) - Another package of PHP components.
* [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.
* [Symfony Components](http://symfony.com/doc/master/components/index.html) - The components that make Symfony.
* [Zend Framework 2 Components](https://packages.zendframework.com/) - The components that make Zend Framework.

## Micro Frameworks
*Micro frameworks and routers.*

* [Bullet PHP](http://bulletphp.com/) - A micro framework for building REST APIs.
* [Lumen](https://lumen.laravel.com) - A micro-framework by Laravel.
* [Proton ★261](alexbilbie/Proton) - A StackPHP compatible micro framework.
* [Radar ★42](radarphp/Radar.Adr) - An Action-Domain-Responder implementation for PHP.
* [Silex](https://silex.sensiolabs.org/) - A micro framework built around Symfony components.
* [Slim](https://www.slimframework.com/) - Another simple micro framework.

## Micro Framework Extras
*Extras related to micro frameworks and routers.*

* [Silex Skeleton ★789](silexphp/Silex-Skeleton) - A project skeleton for Silex.
* [Silex Web Profiler ★181](silexphp/Silex-WebProfiler) - A web debug toolbar for Silex.
* [Slim Skeleton ★631](slimphp/Slim-Skeleton) - A skeleton for Slim.
* [Slim View ★301 ⏳1Y](slimphp/Slim-Views) - A collection of custom views for Slim.

## Routers
*Libraries for handling application routing.*

* [Aura.Router ★307](auraphp/Aura.Router) - A full-featured routing library.
* [Fast Route ★2270](nikic/FastRoute) - A fast routing library.
* [Klein ★2067](klein/klein.php) - A flexible router.
* [Pux ★1202](c9s/Pux) - Another fast routing library.
* [Route ★281](thephpleague/route) - A routing library built on top of Fast Route.

## Templating
*Libraries and tools for templating and lexing.*

* [Aura.View ★54](auraphp/Aura.View) - Provides TemplateView and TwoStepView using PHP as the tempting language, with support for partials, sections, and helpers.
* [Foil ★141](FoilPHP/Foil) - Another native PHP templating library.
* [Lex ★91 ⏳2Y](pyrocms/lex) - A lightweight template parser.
* [MtHaml ★330](arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
* [Mustache ★2531](bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
* [Phly Mustache ★126 ⏳1Y](phly/phly_mustache) - Another PHP implementation of the Mustache template language.
* [PHPTAL](http://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](http://platesphp.com/) - A native PHP templating library.
* [Smarty](http://www.smarty.net/) - A template engine to complement PHP.
* [Twig](https://twig.sensiolabs.org/) - A comprehensive templating language.
* [Tale Jade ★82](Talesoft/tale-jade) - A PHP implementation of the Jade template language.

## Static Site Generators
*Tools for pre-processing content to generate web pages.*

* [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
* [Phrozn ★479](Pawka/phrozn) - Another tool that converts Textile, Markdown and Twig into HTML.
* [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.
* [Spress](http://spress.yosymfony.com) - An extensible tool that converts Markdown and Twig into HTML.

## HTTP
*Libraries for working with HTTP.*

* [Buzz ★1297](kriswallsmith/Buzz) - Another HTTP client.
* [Guzzle]( https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
* [HTTPFul ★1315](nategood/httpful) - A chainable HTTP client.
* [PHP VCR](http://php-vcr.github.io/) - A library for recording and replaying HTTP requests.
* [Requests ★2608](rmccue/Requests) - A simple HTTP library.
* [Retrofit ★97](tebru/retrofit-php) - A library to ease creation of REST API clients.
* [zend-diactoros ★355](zendframework/zend-diactoros) - PSR-7 HTTP Message implementation.

## Scraping
*Libraries for scraping websites.*

* [Embed ★1020](oscarotero/Embed) - An information extractor from any web service or page.
* [Goutte ★5296](FriendsOfPHP/Goutte) - A simple web scraper.
* [PHP Spider ★802](mvdbos/php-spider) - A configurable and extensible PHP web spider.

## Middlewares
*Libraries for building application using middlewares.*

* [Expressive](https://zendframework.github.io/zend-expressive/) - PSR-7 Middleware framework from Zend.
* [PSR7-Middlewares ★539](oscarotero/psr7-middlewares) - Inspiring collection of handy middlewares.
* [Relay ★184](relayphp/Relay.Relay) - A PHP 5.5 PSR-7 middleware dispatcher.
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Silex/Symfony.
* [zend-stratigility ★180](zendframework/zend-stratigility) - Middleware for PHP built on top of PSR-7.

## URL
*Libraries for parsing URLs.*

* [PHP Domain Parser ★425](jeremykendall/php-domain-parser) - A domain suffix parser library.
* [Purl ★691](jwage/purl) - A URL manipulation library.
* [sabre/uri ★113](fruux/sabre-uri) - A functional URI manipulation library.
* [Uri ★214](thephpleague/uri) - Another URL manipulation library.

## Email
*Libraries for sending and parsing email.*

* [CssToInlineStyles ★898](tijsverkoyen/CssToInlineStyles) - A library to inline CSS in email templates.
* [Email Reply Parser ★431](willdurand/EmailReplyParser) - An email reply parser library.
* [Email Validator ★68](nojacko/email-validator) - A small email address validation library.
* [Fetch ★422](tedious/Fetch) - An IMAP library.
* [Mautic ★1625](mautic/mautic) - Email marketing automation
* [PHPMailer ★8776](PHPMailer/PHPMailer) - Another mailer solution.
* [Stampie ★32 ⏳1Y](henrikbjorn/Stampie) - A library for email services such as [SendGrid](https://sendgrid.com/), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [Mandrill](http://www.mandrill.com).
* [SwiftMailer](http://swiftmailer.org/) - A mailer solution.

## Files
*Libraries for file manipulation and MIME type detection.*

* [Apache MIME Types ★43](dflydev/dflydev-apache-mime-types) - A library that parses Apache MIME types.
* [Canal ★28 ⏳4Y](dflydev/dflydev-canal) - A library to determine internet media types.
* [CSV ★1130](thephpleague/csv) - A CSV data manipulation library.
* [Ferret ★19 ⏳2Y](versionable/Ferret) - A MIME detection library.
* [Flysystem ★3351](thephpleague/Flysystem) - Another filesystem abstraction layer.
* [Gaufrette ★1803](KnpLabs/Gaufrette) - A filesystem abstraction layer.
* [Hoa Mime ★75](hoaproject/Mime) - Another MIME detection library.
* [Lurker ★4 ⏳1Y](henrikbjorn/Lurker) - A resource tracking library.
* [PHP FFmpeg ★1528](PHP-FFmpeg/PHP-FFmpeg) - A wrapper for the [FFmpeg](http://www.ffmpeg.org/) video library.
* [UnifiedArchive ★95](wapmorgan/UnifiedArchive) - A unified reader and writer of compressed archives.

## Streams
*Libraries for working with streams.*

* [Streamer ★217](fzaninotto/Streamer) - A simple object-orientated stream wrapper library.

## Dependency Injection
*Libraries that implement the dependency injection design pattern.*

* [Aura.Di ★258](auraphp/Aura.Di) - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
* [Acclimate ★171](AcclimateContainer/acclimate-container) - A common interface to dependency injection containers and service locators.
* [Auryn ★466](rdlowrey/Auryn) - A recursive dependency injector.
* [Container ★263](thephpleague/container) - Another flexible dependency injection container.
* [Disco ★75](bitExpert/disco) - A PSR-11 compatible, annotation-based dependency injection container.
* [PHP-DI](http://php-di.org/) - A dependency injection container that supports autowiring.
* [Pimple](http://pimple.sensiolabs.org/) - A tiny dependency injection container.
* [Symfony DI ★107](symfony/dependency-injection) - A dependency injection container component (SF).

## Imagery
*Libraries for manipulating images.*

* [Color Extractor ★708](thephpleague/color-extractor) - A library for extracting colours from images.
* [GIF Creator ★225](Sybio/GifCreator) - A library to create GIF animations from multiple images.
* [GIF Frame Extractor ★96](Sybio/GifFrameExtractor) - A library to extract GIF animation frame information.
* [Glide ★1042](thephpleague/glide) - An on-demand image manipulation library.
* [Image Hash ★839](jenssegers/imagehash) - A library for generating perceptual image hashes.
* [Image Optimizer ★295](psliwa/image-optimizer) - A library for optimizing images.
* [Image With Text ★88 ⏳3Y](nmcteam/image-with-text) - A library for embedding text into images.
* [Imagine](http://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
* [Intervention Image ★5157](Intervention/image) - Another image manipulation library.
* [PHP Image Workshop ★755](Sybio/ImageWorkshop) - Another image manipulation library.

## Testing
*Libraries for testing codebases and generating test data.*

* [Alice ★1318](nelmio/alice) - An expressive fixture generation library.
* [AspectMock ★554](Codeception/AspectMock) - A mocking framework for PHPUnit/Codeception.
* [Atoum ★1044](atoum/atoum) - A simple testing library.
* [Behat](http://docs.behat.org/en/v2.5/) - A behaviour driven development (BDD) testing framework.
* [Codeception ★2822](Codeception/Codeception) - A full stack testing framework.
* [DBUnit ★164](sebastianbergmann/dbunit) - A database testing library for PHPUnit.
* [Faker ★10939](fzaninotto/Faker) - A fake data generator library.
* [HTTP Mock ★275](InterNations/http-mock) - A library for mocking HTTP requests in unit tests.
* [Kahlan ★679](kahlan/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
* [Mink](http://mink.behat.org/en/latest/) - Web acceptance testing.
* [Mockery ★2322](mockery/mockery) - A mock object library for testing.
* [ParaTest ★462](brianium/paratest) - A parallel testing library for PHPUnit.
* [Peridot ★255](peridot-php/peridot) - An event driven test framework.
* [Phake ★402](mlively/Phake) - Another mock object library for testing.
* [Pho ★277](danielstjules/pho) - Another behaviour driven development testing framework.
* [PHP-Mock ★134](php-mock/php-mock) - A mock library for built-in PHP functions (e.g. time()).
* [PHPSpec ★1198](phpspec/phpspec) - A design by specification unit testing library.
* [PHPT](https://qa.php.net/write-test.php) - A test tool used by PHP itself.
* [PHPUnit ★6125](sebastianbergmann/phpunit) - A unit testing framework.
* [Prophecy ★916](phpspec/prophecy) - A highly opinionated mocking framework.
* [Samsui ★29 ⏳2Y](mauris/samsui) - Another fake data generator library.
* [VFS Stream ★763](mikey179/vfsStream) - A virtual filesystem stream wrapper for testing.
* [VFS ★289](adlawson/php-vfs) - Another virtual filesystem for testing.

## Continuous Integration
*Libraries and applications for continuous integration.*

* [CircleCI](https://circleci.com) - A continuous integration platform.
* [GitlabCi](https://about.gitlab.com/gitlab-ci/) - Let GitLab CI test, build, deploy your code. TravisCi like.
* [Jenkins](https://jenkins.io/index.html) - A continous integration platform with [PHP support](http://jenkins-php.org/index.html).
* [JoliCi ★635](jolicode/JoliCi) - A continuous integration client written in PHP and powered by Docker.
* [PHPCI](https://www.phptesting.org/) - An open source continuous integration platform for PHP.
* [SemaphoreCI](https://semaphoreci.com/) - A continuous integration platform for open source and private projects.
* [Shippable](https://app.shippable.com/) - A docker based continious integration platform for open source and private projects.
* [Sismo](http://sismo.sensiolabs.org/) - A continuous testing server library.
* [Travis CI](https://travis-ci.org/) - A continuous integration platform.
* [Wercker](http://www.wercker.com/) - A continuous integration platform

## Documentation
*Libraries for generating project documentation.*

* [APIGen ★1428](apigen/apigen) - Another API documentation generator.
* [daux.io ★4564](justinwalsh/daux.io) - A documentation generator which uses Markdown files.
* [PHP Documentor 2 ★1925](phpDocumentor/phpDocumentor2) - A documentation generator.
* [phpDox](http://phpdox.de/) - A documentation generator for PHP projects (that is not limited to API documentation).
* [Sami ★1547](FriendsOfPHP/Sami) - An API documentation generator.

## Security
*Libraries for generating secure random numbers, encrypting data and scanning for vulnerabilities.*

* [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium ★4184](jedisct1/libsodium).
* [HTML Purifier ★936](ezyang/htmlpurifier) - A standards compliant HTML filter.
* [IniScan ★1174](psecio/iniscan) - A tool that scans PHP INI files for security.
* [Optimus ★639](jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method.
* [PHP Encryption ★1168](defuse/php-encryption) - Secure PHP Encryption Library.
* [PHP IDS ★540 ⏳1Y](PHPIDS/PHPIDS) - A structured PHP security layer.
* [PHP SSH ★271](Herzult/php-ssh) - An experimental object orientated SSH wrapper library.
* [PHPSecLib](http://phpseclib.sourceforge.net/) - A pure PHP secure communications library.
* [random_compat ★454](paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()`
* [RandomLib ★598](ircmaxell/RandomLib) - A library for generating random numbers and strings.
* [SecurityMultiTool ★110](padraic/SecurityMultiTool) - A PHP security library.
* [SensioLabs Security Check](https://security.sensiolabs.org/) - A web tool to check your Composer dependencies for security advisories.
* [TCrypto ★50](timoh6/TCrypto) - A simple encrypted key-value storage library.
* [VAddy](https://vaddy.net/) - A continuous security testing platform for web applications.
* [Zed](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - An integrated penetration testing tool for web applications.

## Passwords
*Libraries and tools for working with and storing passwords.*

* [GenPhrase ★63](timoh6/GenPhrase) - A library for generating secure random passphrases.
* [Password Compat ★1843](ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
* [Password Policy ★50](ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
* [Password Validator ★133](jeremykendall/password-validator) - A library for validating and upgrading password hashes.
* [Password-Generator ★73](hackzilla/password-generator) - PHP library to generate random passwords.
* [PHP Password Lib ★351 ⏳2Y](ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
* [phpass](http://www.openwall.com/phpass/) - A portable password hashing framework.
* [Zxcvbn PHP ★358](bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS.

## Code Analysis
*Libraries and tools for analysing, parsing and manipulating codebases.*

* [Athletic ★308 ⏳1Y](polyfractal/athletic) - An annotation based benchmark framework.
* [Better Reflection ★340](Roave/BetterReflection) - AST-based reflection library that allows analysis and manipulation of code
* [Code Climate](https://codeclimate.com) - An automated code review.
* [Dissect ★177](jakubledl/dissect) - A set of tools for lexical and syntactical analysis.
* [Exakat ★64](exakat/exakat) - A static analysis engine for PHP.
* [GrumPHP ★1733](phpro/grumphp) - A composer plugin to defend code quality.
* [Mondrian ★324 ⏳1Y](Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
* [PHP Analyser ★446](scrutinizer-ci/php-analyzer) - A library for analysing PHP code to find bugs and errors.
* [PHP Code Sniffer ★3501](squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations.
* [PHP CS Fixer ★4509](FriendsOfPHP/PHP-CS-Fixer) - A coding standards fixer library.
* [PHP Manipulator ★107 ⏳2Y](schmittjoh/php-manipulator) - A library for analysing and modifying PHP Source Code.
* [PHP Mess Detector](https://phpmd.org/) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHP Metrics ★1141](phpmetrics/PhpMetrics) - A static metric library.
* [PHP Migration ★90](monque/PHP-Migration) - A static analyzer for PHP version migration.
* [PHP Parser ★2873](nikic/PHP-Parser) - A PHP parser written in PHP.
* [PHP Refactoring Browser ★544](QafooLabs/php-refactoring-browser) - A command line utility for refactoring PHP code.
* [PHP Semantic Versioning Checker ★361](tomzx/php-semver-checker) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
* [phan ★2128](etsy/phan) - A static analyzer based on PHP 7+ and the php-ast extension.
* [PHPCheckstyle ★83](PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.
* [PHPCPD ★1230](sebastianbergmann/phpcpd) - A library that detects copied and pasted code.
* [PhpDependencyAnalysis ★260](mamuz/PhpDependencyAnalysis) - A tool to create customisable dependency graphs.
* [PHPLOC ★1251](sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project.
* [PHPQA ★124](EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
* [PHPPHP ★636](ircmaxell/PHPPHP) - A PHP VM implementation in PHP.
* [PHPSandbox ★77](Corveda/PHPSandbox) - A PHP sandbox environment.
* [PHPStan ★1862](phpstan/phpstan) - A PHP Static Analysis Tool.
* [Qafoo Quality Analyzer ★381](Qafoo/QualityAnalyzer) - A tool to visualize metrics and source code.
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to scrutinise PHP code.
* [UBench ★422 ⏳2Y](devster/ubench) - A simple micro benchmark library.

## Architectural
*Libraries related to design patterns, programming approaches and ways to organize code.*

* [Compose ★73 ⏳3Y](igorw/compose) - A function composition library.
* [Design Patterns PHP ★12682](domnikl/DesignPatternsPHP) - A repository of software patterns implemented in PHP.
* [Finite](http://yohan.giarel.li/Finite/) - A simple PHP finite state machine.
* [Functional PHP ★956](lstrojny/functional-php) - A functional programming library.
* [Galapagos ★11 ⏳2Y](endel/galapagos) - Evolutionary language transformation.
* [Iter ★572](nikic/iter) - A library that provides iteration primitives using generators.
* [Monad PHP ★199 ⏳1Y](ircmaxell/monad-php) - A simple Monad library.
* [Patchwork](http://patchwork2.org/) - A library for redefining userland functions.
* [PHP Option ★513](schmittjoh/php-option) - An option type library.
* [Pipeline ★359](thephpleague/pipeline) - A pipeline pattern implementation.
* [Ruler ★734](bobthecow/Ruler) - A simple stateless production rules engine.
* [RulerZ ★490](K-Phoen/rulerz) - A powerful rule engine and implementation of the Specification pattern.

## Debugging and Profiling
*Libraries and tools for debugging and profiling code.*

* [APM](http://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
* [Barbushin PHP Console ★964](barbushin/php-console) - Another web debugging console using Google Chrome.
* [Blackfire.io](https://blackfire.io) - A low-overhead code profiler.
* [Kint ★1853](kint-php/kint) - A debugging and profiling tool.
* [PHP Console ★421](Seldaek/php-console) - A web debugging console.
* [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
* [PHPBench ★508](phpbench/phpbench) - A benchmarking Framework.
* [PHPDBG](http://phpdbg.com/) - An interactive PHP debugger.
* [Tideways.io](https://tideways.io/) - Monitoring and profiling tool
* [Tracy ★732](nette/tracy) - A simple error detection, logging and time measuring library.
* [xDebug ★1136](xdebug/xdebug) - A debug and profile tool for PHP.
* [XHProf ★1879](phacility/xhprof) - A profiling tool originally developed by Facebook.
* [Z-Ray](http://www.zend.com/en/products/server/z-ray) - A debug and profile tool for Zend Server.

## Build Tools
*Project build and automation tools.*

* [Bob ★96 ⏳3Y](CHH/bob) - A simple project automation tool.
* [Box ★1019](box-project/box2) - A utility to build PHAR files.
* [Construct ★214](jonathantorres/construct) - A PHP project/micro-package generator.
* [Phake ★380](jaz303/phake) - A rake PHP clone library.
* [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.

## Task Runners
*Libraries for automating and running tasks.*

* [Bldr](http://bldr.io/) - A PHP Task runner built on Symfony components.
* [Jobby ★575](jobbyphp/jobby) - A PHP cron job manager without modifying crontab.
* [Robo ★1646](consolidation/Robo) - A PHP Task runner with object-orientated configurations.
* [Task](http://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.

## Navigation
*Tools for building navigation structures.*

* [Cartographer ★304](tackk/cartographer) - A sitemap generation library.
* [KnpMenu ★448](KnpLabs/KnpMenu) - A menu library.

## Asset Management
*Tools for managing, compressing and minifying website assets.*

* [JShrink ★459](tedious/JShrink) - A JavaScript minifier library.
* [Munee ★851](meenie/munee) - An asset optimiser library.
* [Puli ★435](puli/repository) - A library for determining assets absolute paths.
* [BowerPHP ★475](Bee-Lab/bowerphp) - A PHP implementation of Bower. A package manager for the web

## Geolocation
*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoCoder](http://geocoder-php.org/) - A geocoding library.
* [GeoJSON ★120](jmikola/geojson) - A GeoJSON implementation.
* [GeoTools ★782](thephpleague/geotools) - A library of geo-related tools.
* [PHPGeo ★826](mjaschen/phpgeo) - A simple geo library.

## Date and Time
*Libraries for working with dates and times.*

* [CalendR](http://yohan.giarel.li/CalendR/) - A calendar management library.
* [Carbon ★5556](briannesbitt/Carbon) - A simple DateTime API extension.
* [Chronos ★313](cakephp/chronos) - A DateTime API extension supporting both mutable and immutable date/time.
* [ExpressiveDate ★247](jasonlewis/expressive-date) - Another DateTime API extension.
* [Moment.php ★477](fightbulc/moment.php) - Moment.js inspired PHP DateTime handler with i18n support.
* [Yasumi ★355](azuyalabs/yasumi) - An library to help you calculate the dates and names of holidays.

## Event
*Libraries that are event-driven or implement non-blocking event loops.*

* [Amp ★631](amphp/amp) - An event driven non-blocking I/O library.
* [Broadway ★919](broadway/broadway) - An event source and CQRS library.
* [Cake Event ★10](cakephp/event) - An event dispatcher library (CP).
* [Elephant.io ★904](Wisembly/Elephant.io) - Yet another web socket library.
* [Evenement ★515](igorw/evenement) - An event dispatcher library.
* [Event ★247](thephpleague/event) - An event library with a focus on domain events.
* [Hoa EventSource ★70](hoaproject/Eventsource) - An event source library.
* [Hoa WebSocket ★355](hoaproject/Websocket) - Another web socket library.
* [Prooph Event Store ★191](prooph/event-store) - An event source component to persist event messages
* [Ratchet ★3578](ratchetphp/Ratchet) - A web socket library.
* [React ★5083](reactphp/react) - An event driven non-blocking I/O library.
* [Rx.PHP ★211 ⏳1Y](asm89/Rx.PHP) - A reactive extension library.
* [Workerman ★4386](walkor/Workerman) - An event driven non-blocking I/O library.

## Logging
*Libraries for generating and working with log files.*

* [Analog ★249](jbroadway/analog) - A closure-based micro logging package.
* [KLogger ★773](katzgrau/KLogger) - An easy-to-use PSR-3 compliant logging class.
* [Monolog ★6097](Seldaek/monolog) - A comprehensive logger.

## E-commerce
*Libraries and applications for taking payments and building online e-commerce stores.*

* [Money ★1399](moneyphp/money) - A PHP implementation of Fowler's money pattern.
* [OmniPay ★3539](thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
* [Payum ★973](payum/payum) - A payment abstraction library.
* [Shopware ★641](shopware/shopware) - Highly customizable e-commerce software
* [Swap ★767](florianv/swap) - An exchange rates library.
* [Sylius](http://sylius.org/) - An open source e-commerce solution.

## PDF
*Libraries and software for working with PDF files.*

* [Dompdf ★3664](dompdf/dompdf) - A HTML to PDF converter.
* [PHPPdf ★288](psliwa/PHPPdf) - A library for generating PDFs and images from XML.
* [Snappy ★2204](KnpLabs/snappy) - A PDF and image generation library.
* [WKHTMLToPDF ★5386](wkhtmltopdf/wkhtmltopdf) - A tool to convert HTML to PDF.

## Office
*Libraries for working with office suite documents.*

* [ExcelAnt ★52 ⏳3Y](Wisembly/ExcelAnt) - A library for manipulating Microsoft Excel documents.
* [PHPPowerPoint ★574](PHPOffice/PHPPresentation) - A library for working with Microsoft PowerPoint Presentations.
* [PHPWord ★2387](PHPOffice/PHPWord) - A library for working with Microsoft Word documents.
* [PHPSpreadsheet ★792](PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel)

## Database
*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* [Aura.Sql ★371](auraphp/Aura.Sql) - Provides an extension to the native PDO along with a profiler and connection locator.
* [Aura.SqlQuery ★229](auraphp/Aura.SqlQuery) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server. Edit
* [Baum ★1429](etrepat/baum) - A nested set implementation for Eloquent.
* [Cake ORM ★114](cakephp/orm) - Object-Relational Mapper, implemented using the DataMapper pattern (CP).
* [Doctrine Extensions ★1777](Atlantic18/DoctrineExtensions) - A collection of Doctrine behavioural extensions.
* [Doctrine](http://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [Eloquent ★1060](illuminate/database) - A simple ORM (L5).
* [LazyRecord ★1](corneltek/LazyRecord) - A fast ORM designed for simplicity, extendability and performance.
* [Pomm ★156](chanmix51/Pomm) - An Object Model Manager for PostgreSQL.
* [Propel](http://propelorm.org/) - A fast ORM, migration library and query builder.
* [ProxyManager ★727](Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.
* [RedBean](http://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
* [Spot2 ★481](spotorm/spot2) - A MySQL datamapper ORM.

## Migrations
Libraries to help manage database schemas and migrations.

* [Doctrine Migrations](http://docs.doctrine-project.org/projects/doctrine-migrations/en/latest/toc.html) - A migration library for Doctrine.
* [Migrations ★36](icomefromthenet/Migrations) - A migration management library.
* [Phinx ★2985](robmorgan/phinx) - Another database migration library.
* [PHPMig ★435](davedevelopment/phpmig) - Another migration management library.
* [Ruckusing ★471](ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.

## NoSQL
*Libraries for working with "NoSQL" backends.*

* [Monga ★286 ⏳1Y](thephpleague/monga) - A MongoDB abstraction library.
* [MongoQB ★193 ⏳1Y](alexbilbie/MongoQB) - A MongoDB query builder library.
* [PHPMongo ★148](sokil/php-mongo) - A MongoDB ORM.
* [Predis ★3446](nrk/predis) - A feature complete Redis library.

## Queue
*Libraries for working with event and task queues.*

* [Bernard ★761](bernardphp/bernard) - A multibackend abstraction library.
* [BunnyPHP ★262](jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
* [Pheanstalk ★1130](pda/pheanstalk) - A Beanstalkd client library.
* [PHP AMQP ★1612](php-amqplib/php-amqplib) - A pure PHP AMQP library.
* [Tarantool Queue ★32](tarantool-php/queue) - PHP bindings for Tarantool Queue.
* [Thumper ★219 ⏳1Y](php-amqplib/Thumper) - A RabbitMQ pattern library.

## Search
*Libraries and software for indexing and performing search queries on data.*

* [Elastica ★1420](ruflin/Elastica) - A client library for ElasticSearch.
* [ElasticSearch PHP ★1669](elastic/elasticsearch-php) - The official client library for [ElasticSearch](https://www.elastic.co/).
* [Solarium](http://www.solarium-project.org/) - A client library for [Solr](http://lucene.apache.org/solr/).
* [Sphinx Search ★44 ⏳1Y](ripaclub/sphinxsearch) - Sphinx Search library provides SphinxQL indexing and searching features
* [SphinxQL query builder](http://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](http://sphinxsearch.com/) search engine.

## Command Line
*Libraries related to the command line.*

* [Aura.Cli ★91](auraphp/Aura.Cli) - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.
* [Boris ★2148](borisrepl/boris) - A tiny PHP REPL.
* [Cilex ★574](Cilex/Cilex) - A micro framework for building command line tools.
* [CLI Menu ★747](php-school/cli-menu) - A library for building CLI menus.
* [CLIFramework ★299](c9s/CLIFramework) - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
* [CLImate ★1182](thephpleague/climate) - A library for outputting colours and special formatting.
* [Commando ★605](nategood/commando) - Another simple command line opt parser.
* [Cron Expression ★1088](mtdowling/cron-expression) - A library to calculate cron run dates.
* [GetOpt ★120](ulrichsg/getopt-php) - A command line opt parser.
* [GetOptionKit ★106](c9s/GetOptionKit) - Another command line opt parser.
* [Hoa Console ★221](hoaproject/Console) - Another command line library.
* [OptParse ★15](CHH/optparse) - Another command line opt parser.
* [Pecan ★43 ⏳2Y](mcrumm/pecan) - An event-driven, non-blocking shell.
* [PsySH ★1930](bobthecow/psysh) - Another PHP REPL.
* [ShellWrap ★655](MrRio/shellwrap) - A simple command line wrapper library.

## Authentication and Authorization
*Libraries for implementing user authentication and authorization.*

* [Aura.Auth ★85](auraphp/Aura.Auth) - Provides authentication functionality and session tracking using various adapters.
* [Hawk ★58 ⏳1Y](dflydev/dflydev-hawk) - A Hawk HTTP authentication library.
* [SocialConnect Auth ★242](socialConnect/auth) - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
* [Json Web Token ★1356](lcobucci/jwt) - Json Tokens to authenticate and transmit information.
* [Lock ★925](BeatSwitch/lock) - A library for implementing Access Control Lists (ACL) systems.
* [OAuth 1.0 Client ★135](thephpleague/oauth1-client) - An OAuth 1.0 client library.
* [OAuth 2.0 Client ★1606](thephpleague/oauth2-client) - An OAuth 2.0 client library.
* [OAuth2 Server](http://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* [OAuth2 Server](http://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
* [Opauth ★1567](opauth/opauth) - A multi-provider authentication framework.
* [PHP oAuthLib ★967](Lusitanian/PHPoAuthLib) - Another OAuth library.
* [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
* [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.
* [TwitterOAuth ★3398](abraham/twitteroauth) - A Twitter OAuth library.
* [TwitterSDK ★37 ⏳2Y](lyrixx/twitter-sdk) - A fully tested Twitter SDK.

## Markup
*Libraries for working with markup.*

* [Cebe Markdown ★628](cebe/markdown) - An fast and extensible Markdown parser.
* [Ciconia ★377 ⏳1Y](kzykhys/Ciconia) - Another Markdown parser that supports Github flavoured Markdown.
* [CommonMark PHP ★823](thephpleague/commonmark) - A Markdown parser which supports the full [CommonMark spec](http://spec.commonmark.org/).
* [Decoda ★163](milesj/decoda) - A lightweight markup parser library.
* [Emoji ★30](heyupdate/Emoji) - A library that converts unicode characters and names into emoji images.
* [HTML to Markdown ★576](thephpleague/html-to-markdown) - Converts HTML into Markdown.
* [HTML5 PHP ★424](Masterminds/html5-php) - An HTML5 parser and serializer library.
* [Parsedown ★4316](erusev/parsedown) - Another Markdown parser.
* [PHP Markdown ★2419](michelf/php-markdown) - A Markdown parser.

## Strings
*Libraries for parsing and manipulating strings.*

* [Agent ★1480](jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
* [ANSI to HTML5 ★106](sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library.
* [Color Jizz ★223](mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours.
* [Device Detector ★786](piwik/device-detector) - Another library for parsing user agent strings.
* [Hoa String ★97](hoaproject/Ustring) - Another UTF-8 string library.
* [Jieba-PHP ★337](fukuball/jieba-php) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
* [Mobile-Detect ★6961](serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).
* [Patchwork UTF-8 ★56 ⏳1Y](nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
* [Slugify ★1033](cocur/slugify) - A library to convert strings to slugs.
* [SQL Formatter ★567](jdorn/sql-formatter) - A library for formatting SQL statements.
* [Stringy ★1832](danielstjules/Stringy) - A string manipulation library with multibyte support.
* [Text ★46 ⏳3Y](kzykhys/Text) - A text manipulation library.
* [UA Parser](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
* [URLify ★511](jbroadway/urlify) - A PHP port of Django's URLify.js.
* [UUID ★2351](ramsey/uuid) - A library for generating UUIDs.

## Numbers
*Libraries for working with numbers.*

* [ByteUnits ★46](gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
* [LibPhoneNumber for PHP ★1851](giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.
* [Math ★88](moontoast/math) - A library for working with large numbers.
* [Numbers PHP ★150 ⏳1Y](powder96/numbers.php) - A library for working with numbers.
* [PHP Conversion ★78 ⏳1Y](Crisu83/php-conversion) - Another library for converting between units of measure.
* [PHP Units of Measure ★7](triplepoint/php-units-of-measure) - A library for converting between units of measure.

## Filtering and Validation
*Libraries for filtering and validating data.*

* [Aura.Filter ★103](auraphp/Aura.Filter) - Provides tools to validate and sanitize objects and arrays.
* [Cake Validation ★18](cakephp/validation) - Another validation library (CP).
* [DMS Filter ★78 ⏳1Y](rdohms/DMS-Filter) - An annotation filtering library.
* [Filterus ★374](ircmaxell/filterus) - A simple PHP filtering library.
* [ISO-codes ★462](ronanguilloux/IsoCodes) - A library for validating inputs according standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries
* [MetaYaml ★58 ⏳1Y](romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
* [Respect Validation ★3894](Respect/Validation) - A simple validation library.
* [Upload ★1356](brandonsavage/Upload) - A library for handling file uploads and validation.
* [Valitron ★831](vlucas/valitron) - Another validation library.
* [Volan ★32](serkin/Volan) - Another simplified validation library.

## API
*Libraries and web tools for developing APIs.*

* [API Platform](https://api-platform.com ) - Expose in minutes an hypermedia REST API that embraces JSON-LD, Hydra format.
* [Apigility ★456](zfcampus/zf-apigility-skeleton) - An API builder built with Zend Framework 2.
* [Drest ★82](leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints.
* [HAL ★184](blongden/hal) - A Hypertext Application Language (HAL) builder library.
* [Hateoas ★748](willdurand/Hateoas) - A HATEOAS REST web service library.
* [Negotiation ★397](willdurand/Negotiation) - A content negotiation library.
* [Restler ★1193](Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
* [wsdl2phpgenerator ★562](wsdl2phpgenerator/wsdl2phpgenerator) - A tool to generate PHP classes from SOAP WSDL files.

## Caching
*Libraries for caching data.*

* [Alternative PHP Cache (APC)](http://php.net/manual/en/book.apc.php) - Open opcode cache for PHP.
* [APIx Cache ★48](frqnck/apix-cache) - A thin PSR-6 cache wrapper to various caching backends emphasising cache tagging and indexing.
* [CacheTool ★372](gordalina/cachetool) - A tool to clear APC/opcode caches from the command line.
* [Cake Cache ★11](cakephp/cache) - A caching library (CP).
* [Doctrine Cache ★302](doctrine/cache) - A caching library.
* [Metaphore ★76](sobstel/metaphore) - Cache slam defense using a semaphore to prevent dogpile effect.
* [Stash ★794](tedious/Stash) - Another library for caching.
* [Zend Cache ★21](zendframework/zend-cache) - Another caching library (ZF2).

## Data Structure and Storage
*Libraries that implement data structure or storage techniques.*

* [Ardent ★571](morrisonlevi/Ardent) - A library of data structures.
* [Cake Collection ★28](cakephp/collection) - A simple collections library (CP).
* [Collections ★46](italolelis/collections) - Collections Abstraction library for PHP.
* [Fractal ★1922](thephpleague/fractal) - A library for converting complex data structures to JSON output.
* [Ginq ★149](akanehara/ginq) - Another PHP library based on .NET's LINQ.
* [JsonMapper ★554](cweiske/jsonmapper) - A library that maps nested JSON structures onto PHP classes.
* [Knapsack ★298](DusanKasan/Knapsack) - Collection library inspired by Clojure's sequences.
* [PHP Collections ★243](schmittjoh/php-collection) - A simple collections library.
* [PINQ ★378](TimeToogo/Pinq) - A PHP library based on .NET's LINQ (Language Integrated Query).
* [Porter ★334](ScriptFUSION/Porter) - Data import abstraction framework.
* [Serializer ★601](schmittjoh/serializer) - A library for serialising and de-serialising data.
* [Totem ★69](Wisembly/Totem) - A library to manage and create data changesets.
* [YaLinqo ★253](Athari/YaLinqo) - Yet Another LINQ to Objects for PHP.
* [Zend Serializer ★9](zendframework/zend-serializer) - Another library for serialising and de-serialising data (ZF2).

## Notifications
*Libraries for working with notification software.*

* [JoliNotif ★673](jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
* [Nod ★47 ⏳4Y](filp/nod) - A notification library (e.g., Growl).
* [Notification Pusher ★870](Ph3nol/NotificationPusher) - A standalone library for device push notifications.
* [Notificato ★195 ⏳1Y](mac-cain13/notificato) - A library for handling push notifications.
* [Notificator ★134](namshi/notificator) - A lightweight notification library.
* [Php-pushwoosh ★41](gomoob/php-pushwoosh) - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services.

## Deployment
*Libraries for project deployment.*

* [Deployer ★4215](deployphp/deployer) - A deployment tool.
* [Envoy ★902](laravel/envoy) - A tool to run SSH tasks with PHP.
* [Plum ★90 ⏳1Y](aerialls/Plum) - A deployer library.
* [Pomander ★201](tamagokun/pomander) - A deployment tool for PHP applications.
* [Rocketeer ★2404](rocketeers/rocketeer) - A fast and easy deployer for the PHP world.

## Internationalisation and Localisation
*Libraries for Internationalization (I18n) and Localization (L10n).*

* [Aura.Intl ★63](auraphp/Aura.Intl) - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
* [Cake I18n ★12](cakephp/i18n) - Message translation and localization for dates and numbers (CP)

## Third Party APIs
*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK ★2468](aws/aws-sdk-php) - The official PHP AWS SDK library.
* [Campaign Monitor](http://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
* [Digital Ocean ★157 ⏳2Y](toin0u/DigitalOcean) - A library to interface with the Digital Ocean API.
* [Dropbox SDK ★211](dropbox/dropbox-sdk-php) - The official PHP Dropbox SDK library.
* [Github ★64 ⏳3Y](dsyph3r/github-api3-php) - A library to interface with the Github API.
* [Mailgun ★558](mailgun/mailgun-php) The official Mailgun PHP API.
* [PHP Github API ★1070](KnpLabs/php-github-api) - Another library to interface with the Github API.
* [S3 Stream Wrapper ★17](gwkunze/S3StreamWrapper) - A stream wrapper library for Amazon S3.
* [Stripe ★1118](stripe/stripe-php) - The official Stripe PHP library.
* [Twilio ★821](twilio/twilio-php) - The official Twilio PHP REST API.
* [Twitter OAuth ★7 ⏳3Y](widop/twitter-oauth) - A library to interface with Twitter's OAuth workflow.
* [Twitter REST ★24 ⏳3Y](widop/twitter-rest) - A library to interact with Twitter's REST API.

## Extensions
*Libraries to help build PHP extensions.*

* [PHP CPP](http://www.php-cpp.com/) - A C++ library for developing PHP extensions.
* [Zephir ★1915](phalcon/zephir) - A compiled language between PHP and C++ for developing PHP extensions.

## Miscellaneous
*Useful libraries or tools that don't fit in the categories above.*

* [Annotations ★194](doctrine/annotations) - An annotations library (part of Doctrine).
* [Cake Utility ★31](cakephp/utility) - Utility classes such as Inflector, String, Hash, Security and Xml (CP).
* [Chief ★36](adamnicholson/Chief) - A command bus library.
* [ClassPreloader ★217](ClassPreloader/ClassPreloader) - A library for optimising autoloading.
* [Country List ★2849](umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
* [Embera ★143](mpratt/Embera) - An Oembed consumer library.
* [Essence ★585](essence/essence) - A library for extracting web media.
* [Flux ★314](selvinortiz/flux) - A regular expression building library.
* [Graphviz ★41](alexandresalome/graphviz) - A Graphviz library.
* [Hprose-PHP ★796](hprose/hprose-php) - A very newbility RPC Library, support 25+ languages now.
* [JSON Lint ★234](Seldaek/jsonlint) - A JSON lint utility.
* [JSONPCallbackValidator ★41](willdurand/JsonpCallbackValidator) - A library for validating JSONP callbacks.
* [Jumper ★40 ⏳3Y](kakawait/Jumper) - A remote service executor library.
* [LadyBug ★443](raulfraile/Ladybug) - A dumper library.
* [Lambda PHP ★19 ⏳3Y](igorw/lambda-php) - A Lambda calculus interpreter in PHP.
* [LiteCQRS ★470 ⏳2Y](beberlei/litecqrs-php) - A CQRS (Command Query Responsibility Separation) library.
* [Metrics ★192](beberlei/metrics) - A simple metrics API library.
* [noCAPTCHA ★151](ARCANEDEV/noCAPTCHA) - Helper for Google's noCAPTCHA (reCAPTCHA).
* [Nmap ★70](willdurand/nmap) - A PHP wrapper around [Nmap](https://nmap.org/).
* [Opengraph ★76 ⏳1Y](euskadi31/Opengraph) - An opengraph library.
* [Pagerfanta ★674](whiteoctober/Pagerfanta) - A pagination library.
* [PHP Expression ★31 ⏳3Y](Kitano/php-expression) - A PHP expression language.
* [PHP PassBook ★178](eymengunay/php-passbook) - A PHP library for iOS PassBook.
* [PHP-GPIO ★203 ⏳1Y](ronanguilloux/php-gpio) - A library for playing with the Raspberry PI's GPIO pins.
* [PHP-ML ★3365](php-ai/php-ml) - A library for Machine Learning in PHP.
* [PHPCR ★369](phpcr/phpcr) - A PHP port of the Java Content Repository (JCR).
* [PHPStack](http://dunkels.com/adam/phpstack/) - A TCP/IP stack proof of concept written in PHP.
* [print_o ★65](koriym/print_o) - An object graph visualizer.
* [Procrastinator ★44](lstrojny/Procrastinator) - A library for running time consuming tasks.
* [Prooph Service Bus ★233](prooph/service-bus) - Lightweight message bus supporting CQRS and Micro Services
* [RMT ★346](liip/RMT) - A library for versioning and releasing software.
* [sabre/vobject ★332](fruux/sabre-vobject) - A library for parsing VCard and iCalendar objects.
* [Slimdump ★35](webfactory/slimdump) - An easy dumper tool for MySQL.
* [Spork ★577 ⏳1Y](kriswallsmith/spork) - A process forking library.
* [Sslurp ★60 ⏳2Y](EvanDotPro/Sslurp) - A library that makes dealing with SSL suck less.
* [SuperClosure ★634](jeremeamia/super_closure) - A library that allows Closures to be serialized.
* [Symfony VarDumper](http://symfony.com/doc/current/components/var_dumper.html) - A variable dumper component (SF).
* [Underscore](http://anahkiasen.github.io/underscore-php/) - A PHP port of the Underscore JS library.
* [Whoops ★4041](filp/whoops) - A pretty error handling library.

# Software
*Software for creating a development environment.*

## PHP Installation
*Tools to help install and manage PHP on your computer.*

* [HomeBrew PHP ★2386](Homebrew/homebrew-php) - A PHP tap for HomeBrew.
* [HomeBrew](https://brew.sh/) - A package manager for OSX.
* [PHP Brew ★2937](phpbrew/phpbrew) - A PHP version manager and installer.
* [PHP Build ★692](php-build/php-build) - Another PHP version installer.
* [PHP Env ★519](CHH/phpenv) - Another PHP version manager.
* [PHP OSX](https://php-osx.liip.ch/) - A PHP installer for OSX.
* [PHP Switch ★90 ⏳2Y](jubianchi/phpswitch) - Another version manager.
* [VirtPHP](http://virtphp.org/) - A tool for creating and managing isolated PHP environments.

## Development Environment
*Software and tools for creating a sandboxed development environment.*

* [Ansible](https://www.ansible.com/) - A radically simple orchestration framework.
* [Phansible](http://phansible.com/) - A web tool for building PHP development virtual machines with Ansible.
* [Protobox](http://getprotobox.com/) - Another web tool for building PHP development virtual machines.
* [PuPHPet](https://puphpet.com/) - A web tool for building PHP development virtual machines.
* [Puppet](https://puppet.com/) - A server automation framework and application.
* [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.
* [Docker](https://www.docker.com/) - A containerization platform.

## Virtual Machines
*Alternative PHP virtual machines.*

* [Hack](http://hacklang.org/) - A programming language for HHVM that interoperates seamlessly with PHP.
* [HHVM ★14563](facebook/hhvm) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
* [HippyVM ★858 ⏳1Y](hippyvm/hippyvm) - Another PHP virtual machine.

## Integrated Development Environment
*Integrated Development Environments with support for PHP.*

* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* [Netbeans](https://netbeans.org) - An IDE with support for PHP and HTML5.
* [PhpStorm](http://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.

## Web Applications
*Web-based applications and tools.*

* [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
* [DBV](https://dbv.vizuina.com/) - A database version control application.
* [PHP Queue ★563](CoderKungfu/php-queue) - An application for managing queueing backends.
* [MailCatcher ★3868](sj26/mailcatcher) - A web tool for capturing and viewing emails.
* [Cachet ★6391](cachethq/cachet) - The open source status page system.
* [phpBeanstalkdAdmin ★118 ⏳2Y](mnapoli/phpBeanstalkdAdmin) - Monitoring and administration interface for Beanstalkd.
* [phpRedisAdmin ★1470](ErikDubbelboer/phpRedisAdmin) - A simple web interface to manage [Redis](https://redis.io/) databases.
* [phpPgAdmin ★231](phppgadmin/phppgadmin) - A web-based administration tool for PostgreSQL.
* [phpMyAdmin ★2298](phpmyadmin/phpmyadmin) - A web interface for MySQL/MariaDB.
* [Adminer](https://www.adminer.org/) - Database management in a single PHP file.
* [Grav ★6858](getgrav/grav) - A modern flat-file CMS.

## Infrastructure
*Infrastructure for providing PHP applications and services.*

* [appserver.io](http://appserver.io/) - A multithreaded application server for PHP, written in PHP.
* [php-pm ★3004](php-pm/php-pm) - A process manager, supercharger and load balancer for PHP applications.

# Resources
Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

## PHP Websites
*Useful PHP-related websites.*

* [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
* [PHP Best Practices](https://phpbestpractices.org/) - A PHP best practice guide.
* [PHP FIG](http://www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP Mentoring](https://php-mentoring.org/) - Peer to peer PHP mentorship organization.
* [PHP Package Development Standards](http://php-pds.com) - Package development standards for PHP.
* [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
* [PHP Security](http://phpsecurity.readthedocs.io/en/latest/index.html) - A guide to PHP security.
* [PHP The Right Way](http://www.phptherightway.com/) - A PHP best practice quick reference guide.
* [PHP UG](http://php.ug) - A website to help people locate their nearest PHP user group (UG).
* [PHP Versions](http://phpversions.info/) - Lists which versions of PHP are available on several popular web hosts.
* [PHP Weekly](http://www.phpweekly.com/archive.html) - A weekly PHP newsletter.
* [PHPTrends](https://phptrends.com/) - An overview of fastest growing PHP libraries.
* [Securing PHP](http://securingphp.com/) - A newsletter about PHP security and library recommendations.
* [Seven PHP](http://7php.com/) - A website that interviews members of the PHP community.

## Other Websites
*Useful websites related to web development.*

* [Atlassian Git Tutorials](https://www.atlassian.com/git) - A series of Git tutorials.
* [Hg Init](http://hginit.com/) - A series of Mercurial tutorials.
* [Semantic Versioning](http://semver.org/) - A website explaining semantic versioning.
* [Servers for Hackers](https://serversforhackers.com/) - A newsletter about server management.
* [The Open Web Application Security Project (OWASP)](https://www.owasp.org/index.php/Main_Page) - An open software security community.
* [WebSec IO](https://websec.io/) - A web security community resource.

## PHP Books
*Fantastic PHP-related books.*

* [Functional Programming in PHP](https://www.functionalphp.com/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
* [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
* [Mastering Object-Orientated PHP](http://www.brandonsavage.net) - A book about object-orientated PHP by Brandon Savage.
* [Modern PHP New Features and Good Practices](http://shop.oreilly.com/product/0636920033868.do) - A book about new PHP features and best practices by Josh Lockhart.
* [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
* [PHP 7 Upgrade Guide](https://leanpub.com/php7) - An ebook covering all of the features and changes in PHP 7 by Colin O'Dell.
* [PHP Pandas](https://daylerees.com/php-pandas/) - A book about learning to write PHP by Dayle Rees.
* [Scaling PHP Applications](http://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* [The Grumpy Programmer's Guide to Building Testable PHP Applications](https://leanpub.com/grumpy-testing) - A book about building testing PHP applications by Chris Hartjes.
* [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.
* [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.

## Other Books
*Books related to general computing and web development.*

* [Elasticsearch: The Definitive Guide](https://www.elastic.co/guide/index.html) - A guide to working with Elasticsearch by Clinton Gormley and Zachary Tong.
* [Eloquent JavaScript](http://eloquentjavascript.net/) - A book about JavaScript programming by Marijn Haverbeke.
* [Head First Design Patterns](http://www.headfirstlabs.com/books/hfdp/) - A book that expains software design patterns.
* [Pro Git](https://git-scm.com/book/en/v2) - A book about Git by Scott Chacon and Ben Straub.
* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Tangled Web — Securing Web Applications](https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886) - A book about securing web applications by Michal Zalewski.
* [Understanding Computation](http://computationbook.com) - A book about computation theory by Tom Stuart.
* [Vagrant Cookbook](https://leanpub.com/vagrantcookbook) - A book about creating Vagrant environments by Erika Heidi.

## PHP Videos
*Fantastic PHP-related videos.*

* [Nomad PHP Lightning Talks](https://www.youtube.com/c/nomadphp) - 10 to 15 minute Lightning Talks by PHP community members.
* [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.
* [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* [Taking PHP Seriously](https://www.infoq.com/presentations/php-history) - A talk outlining PHP's strengths by Keith Adams of Facebook.

## PHP Podcasts
*Podcasts with a main focus on PHP topics*

* [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* [Voices of the ElePHPant](https://voicesoftheelephpant.com/) Interviews with the people that make the PHP community special.
* [PHP Roundtable](https://www.phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.

## PHP Reading
*PHP-releated reading materials.*

* [Composer Primer](https://daylerees.com/composer-primer/) - A Composer primer.
* [Composer Stability Flags](https://igor.io/2013/02/07/composer-stability-flags.html) - An article about Composer stability flags.
* [Composer Versioning](https://igor.io/2013/01/07/composer-versioning.html) - An article about Composer versioning.
* [Create Your Own PHP Framework](http://fabien.potencier.org/create-your-own-framework-on-top-of-the-symfony2-components-part-1.html) - A series of articles on how to make your own PHP framework by Fabien Potencier.
* [Don't Worry About BREACH](http://blog.ircmaxell.com/2013/08/dont-worry-about-breach.html) - An article about the BREACH hack and CSRF tokens.
* [On PHP 5.3, Lambda Functions and Closures](http://fabien.potencier.org/on-php-5-3-lambda-functions-and-closures.html) - An article about lambda functions and closures.
* [PHP Is Much Better Than You Think](http://fabien.potencier.org/php-is-much-better-than-you-think.html) - An article about the PHP language and ecosystem.
* [PHP Package Checklist](http://phppackagechecklist.com/) - A checklist for successful PHP package development.
* [PHP Sucks! But I Like It!](http://blog.ircmaxell.com/2012/04/php-sucks-but-i-like-it.html) - An article about the pros and cons of PHP.
* [Preventing CSRF Attacks](http://blog.ircmaxell.com/2013/02/preventing-csrf-attacks.html) - An article on preventing CSRF attacks.
* [Seven Ways to Screw Up BCrypt](http://blog.ircmaxell.com/2012/12/seven-ways-to-screw-up-bcrypt.html) - An article about correct BCrypt implementation.
* [Use Env](https://seancoates.com/blogs/use-env/) - An article about using the unix environment helper.

## PHP Internals Reading
*Reading materials related to the PHP internals or performance.*

* [Disproving the Single Quotes Myth](http://nikic.github.io/2012/01/09/Disproving-the-Single-Quotes-Performance-Myth.html) - An article about performance of single and double quoted strings.
* [How Big Are PHP Arrays (And Values) Really?](http://nikic.github.io/2011/12/12/How-big-are-PHP-arrays-really-Hint-BIG.html) - An article about array internals.
* [How Foreach Works](http://stackoverflow.com/questions/10057671/how-does-php-foreach-actually-work/14854568#14854568) - A detailed StackOverflow answer about foreach.
* [How Long is a Piece of String](http://blog.golemon.com/2006/06/how-long-is-piece-of-string.html) - An article about string internals.
* [PHP Evaluation Order](https://gist.github.com/nikic/6699370) - An article about evaluation order in PHP.
* [PHP Internals Book](http://www.phpinternalsbook.com) - An online book about PHP internals, written by three core developers.
* [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* [Print vs Echo, Which One is Faster?](http://fabien.potencier.org/print-vs-echo-which-one-is-faster.html) - An article about print and echo performance.
* [The PHP Ternary Operator. Fast or Not?](http://fabien.potencier.org/the-php-ternary-operator-fast-or-not.html) - An article ternary performance.
* [Understanding OpCodes](http://blog.golemon.com/2008/01/understanding-opcodes.html) - An article about opcodes.
* [When Does Foreach Copy?](http://nikic.github.io/2011/11/11/PHP-Internals-When-does-foreach-copy.html) - An article about the internals of foreach.
* [Why Objects (Usually) Use Less Memory Than Arrays](https://gist.github.com/nikic/5015323) - An article about object and array internals.
* [You're Being Lied To](http://blog.golemon.com/2007/01/youre-being-lied-to.html) - An article about internal ZVALs.
* Collecting Garbage: [1](http://php.net/manual/en/features.gc.refcounting-basics.php) [2](http://php.net/manual/en/features.gc.collecting-cycles.php) [3](http://php.net/manual/en/features.gc.performance-considerations.php) - A series about the PHP garbage collection internals.
* PHP Source Code for Developers: [1](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers.html) [2](http://nikic.github.io/2012/03/16/Understanding-PHPs-internal-function-definitions.html) [3](http://blog.ircmaxell.com/2012/03/phps-source-code-for-php-developers_21.html) [4](http://nikic.github.io/2012/03/28/Understanding-PHPs-internal-array-implementation.html) - A series about the PHP source code.

## PHP Magazines
*Fantastic PHP-related magazines.*

* [php[architect]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.
---
<p align="center">
	This list is a copy of <a href="ziadoz/awesome-php">ziadoz/awesome-php</a> with ranks
</p>
