<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="janikvonrotz/awesome-powershell">janikvonrotz/awesome-powershell</a> with ranks
</p>
---
# Awesome PowerShell [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

[<img src="https://github.com/PowerShell/PowerShell/raw/master/assets/Powershell_256.png" align="right" width="80">](https://msdn.microsoft.com/en-us/powershell/)

A curated list of delightful [PowerShell](https://en.wikipedia.org/wiki/PowerShell) packages and resources.

PowerShell is a cross-platform (Windows, Linux, and macOS) automation and configuration tool that is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models.
It includes a command-line shell and an associated scripting language.

## Contents

* [API Wrapper](#api-wrapper)
* [Blogs](#blogs)
* [Build Tools](#build-tools)
* [Code and Package Repositories](#code-and-package-repositories)
* [Commandline Productivity](#commandline-productivity)
* [Communities](#communities)
* [Documentation Helper](#documentation-helper)
* [Frameworks](#frameworks)
* [Editors and IDEs](#editors-and-ides)
* [Package Managers](#package-managers)
* [Parallel Processing](#parallel-processing)
* [Podcasts](#podcasts)
* [Security](#security)
* [Testing](#testing)
* [Themes](#themes)
* [Videos](#videos)
* [Webserver](#webserver)
* [SharePoint](#sharepoint)
* [SQL Server](#sql-server)
* [Misc](#misc)

## API Wrapper

- [PSGitHub ★35](pcgeek86/PSGitHub) - This PowerShell module contains commands to manage GitHub through its REST API. 
- [Posh-Github ★50](Iristyle/Posh-GitHub) - Powershell cmdlets that expose the GitHub API.
- [Posh-Gist ★17 ⏳1Y](dfinke/Posh-Gist) - PowerShell cmdlets for interacting with GitHub Gist.
- [PSGist ★10](dotps1/PSGist) - A PowerShell module to work with GitHub Gists. http://dotps1.github.io/PSGist.
- [PSAppVeyor ★7](dotps1/PSAppVeyor) - A PowerShell Module to interact with the AppVeyor REST Api.
- [PSSlack ★55](RamblingCookieMonster/PSSlack) - PowerShell module for simple Slack integration http://ramblingcookiemonster.github.io/PSSlack/


## Blogs

- [Windows PowerShell Blog](https://blogs.msdn.microsoft.com/powershell/) - Official PowerShell Team Blog.
- [Hey, Scripting Guy! Blog](http://blogs.technet.com/b/heyscriptingguy/) - Popular Microsoft blog.
- [Learn Powershell | Achieve More](http://learn-powershell.net/) - Personal blog of Boe Prox who moderated for the Scripting Guy.
- [PowerShellMagazine](http://www.powershellmagazine.com/) - Awesome magazine.
- [Doug Finke](https://dfinke.github.io/#blog) - Author of [PowerShell for Developers](http://shop.oreilly.com/product/0636920024491.do).
- [Mike F. Robbins](http://mikefrobbins.com/) - Microsoft MVP. SAPIEN Tech MVP. Co-author of Windows PowerShell TFM 4th Edition.

## Build Tools

* [psake ★958](psake/psake) - Build automation tool inspired by rake (aka make in Ruby) and bake (aka make in Boo).
* [Invoke-Build ★167](nightroman/Invoke-Build) - Build and test automation tool inspired by psake.
* [PSDeploy ★116](RamblingCookieMonster/PSDeploy) - Module built for the purpose of simplifying multiple types of deployments.
* [BuildHelpers ★43](RamblingCookieMonster/BuildHelpers) - Variety of helper functions for CI/CD scenarios.
* [YDeliver ★31 ⏳2Y](manojlds/YDeliver) - Build and deployment framework aimed at .NET projects.

## Code and Package Repositories

- [GitHub](https://github.com/search?l=powershell&q=stars%3A%3E1&s=stars&type=Repositories) - Looking for an Open Source PowerShell project? It's probably here.
- [PowerShell Code Repository](http://poshcode.org/) - Wide variety of PowerShell code from snippets to modules.
- [PowerShell Gallery](https://www.powershellgallery.com/) - Offical PowerShell package repository, used by PowerShellGet.
- [TechNet Gallery](https://gallery.technet.microsoft.com/) - Wide variety of PowerShell code from snippets to modules.

## Commandline Productivity

- [posh-git ★2242](dahlbyk/posh-git) - Set of PowerShell scripts which provide Git/PowerShell integration.
- [PSReadLine ★847](lzybkr/PSReadLine) - Bash inspired readline implementation for PowerShell. Keeps history between sessions, adds reverse-history search and makes the commandline experience much better overall.
- [TabExpansionPlusPlus ★102](lzybkr/TabExpansionPlusPlus) - PowerShell module to make customizing tab completion easier and add a library of custom argument completers.
- [Jump-Location](https://github.com/tkellogg/Jump-Location) - Powershell `cd` that reads your mind. [Autojump ★5506](wting/autojump) implementation for powershell.
- [Zlocation](https://github.com/vors/ZLocation) - [z.sh ★6816](rupa/z) implementation for PowerShell. Similar to Jump-Location.
- [thefuck ★28102](nvbn/thefuck) - Magnificent app which corrects your previous console command (by typing `fuck`).
- [pslinq ★23 ⏳2Y](manojlds/pslinq) - LINQ (LINQ2Objects) for Powershell.
- [posh-with ★3](JanJoris/posh-with) - Command prefixing for continuous workflow using a single tool.
- [poco](https://gist.github.com/yumura/8df37c22ae1b7942dec7) - [peco ★3922](peco/peco) implementation. Interactive filtering tool.

## Communities

- [PowerShell.com](http://powershell.com/cs/) - Forums, blog posts, and more.
- [PowerShell.org](http://powershell.org/) - Forums, summits, community blog posts, and more.
- [/r/PowerShell](http://www.reddit.com/r/powershell) - Reddit PowerShell community.
- [Slack PowerShell team](http://slack.poshcode.org/) - Large chat room dedicated to PowerShell. Bridged with `#PowerShell` on irc.freenode.net.
- [Twitter #PowerShell](https://twitter.com/search?q=%23PowerShell&src=hash) - Vibrant PowerShell community; great way to keep up with news and blog content.

## Documentation Helper

- [platyPS ★148](PowerShell/platyPS) - Write PowerShell External Help in Markdown.
- [Invoke-CreateModuleHelpFile ★15 ⏳2Y](gravejester/Invoke-CreateModuleHelpFile) - PowerShell function to create a HTML help file for a module and all it's commands. 

## Editors and IDEs

- [PowerShell Studio](https://www.sapien.com/software/powershell_studio) - Powerful PowerShell IDE with module, help, and user interface development tools, high DPI support and regular updates.
- [PowerShell for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell) - Provides IntelliSense, code navigations, script analysis, script debugging, and more for the [Visual Studio Code](https://code.visualstudio.com) editor.
- [PoshTools for Visual Studio ★536](adamdriscoll/PoshTools) - Provides IntelliSense, script debugging, and Pester testing support for PowerShell to Visual Studio.
- [PowerShell ISE](https://msdn.microsoft.com/en-us/powershell/scripting/core-powershell/ise/using-the-windows-powershell-ise) - Official PowerShell development environment included with Microsoft Windows.
- [ISE Steroids](http://www.powertheshell.com/isesteroids/) - Add-on for the PowerShell ISE which provides a rich set of additional features to complete the ISE development experience.
- [PowerGui](http://en.community.dell.com/techcenter/powergui/w/wiki) - Powerful IDE for editing and executing scripts locally and remotely.
- [PowerShell Plus](https://www.idera.com/productssolutions/freetools/powershellplus) - All in one IDE.
- [SublimeText package ★203](SublimeText/PowerShell) - PowerShell language support for Sublime Text.
- [Atom package](https://github.com/jugglingnutcase/language-powershell) - PowerShell language support for Atom.

## Frameworks

- [Carbon](http://get-carbon.org/) - DevOps for automating the configuration of Windows computers.
- [PowerShell PowerUp ★23 ⏳1Y](janikvonrotz/PowerShell-PowerUp) - Powerfull server management framework.
- [PSCX](https://pscx.codeplex.com/) - Useful set of additional cmdlets.
- [PlatyPS ★148](PowerShell/platyPS) - Write PowerShell External Help in Markdown.

## Package Managers

- [PowershellGet ★73](powershell/powershellget) - PowerShellGet is the Package Manager for PowerShell https://www.PowerShellGallery.com 
- [PsGet](http://psget.net/) - Set of commands to install modules from central directory, local file or from the web.
- [Chocolatey](https://chocolatey.org/) - The package manager for Windows. The sane way to manage software on Windows.

## Parallel Processing

- [PoshRSJob ★190](proxb/PoshRSJob) - Provides an alternative to PSjobs with greater performance and less overhead to run commands in the background.
- [Invoke-Parallel ★121](RamblingCookieMonster/Invoke-Parallel) - This function will take in a script or scriptblock, and run it against specified objects(s) in parallel.

## Podcasts

- [PowerScripting](https://powershell.org/podcast/) - Weekly show run by Jon Walz and Hal Rottenberg.

## Security

- [File System Security](https://gallery.technet.microsoft.com/scriptcenter/1abd77a5-9c0b-4a2b-acef-90dbb2b84e85) - Allows a much easier management of permissions on files and folders.
- [PowerShellArsenal ★353](mattifestation/PowerShellArsenal) - Module used to aid a reverse engineer.
- [PowerTools](https://github.com/Veil-Framework/PowerTools) - Collection of projects with a focus on offensive operations.
- [PowerForensics ★557](Invoke-IR/PowerForensics) - Popular live disk forensics platform for windows.
- [PowerSploit ★2606](PowerShellMafia/PowerSploit) - Post-exploitation framework.
- [PowerShellEmpire](https://github.com/PowerShellEmpire/Empire) - Post-exploitation agent.
- [PSReflect ★49](mattifestation/PSReflect) - Easily define in-memory enums, structs, and Win32 functions in PowerShell.
  Useful for attacks, [example](https://github.com/FuzzySecurity/PowerShell-Suite/tree/master/Bypass-UAC).

## Testing

- [Pester ★1054](pester/Pester) - Powershell BDD style testing framework.

## Themes

- [Oh-My-Posh ★177](JanJoris/oh-my-posh) - Tons of beautiful theme that can be enabled by one single command (includes many awesome powerline theme).
- [Powerline ★123](Jaykul/PowerLine) - PowerShell Classes for richer output and prompts.

## Videos

- [Getting Started With PowerShell 3.0 Jump Start](https://mva.microsoft.com/en-US/training-courses/getting-started-with-powershell-30-jump-start-8276) - Jump starts series are for IT professionals with no previous experience with PowerShell, and want to learn it fast.
- [Advanced Tools & Scripting with PowerShell 3.0](https://channel9.msdn.com/Series/advpowershell3) - IT pros, take this advanced PowerShell course to find out how to turn your real time management and automation scripts into useful reusable tools and cmdlets.
- [What's New in PowerShell v5](https://mva.microsoft.com/en-US/training-courses/whats-new-in-powershell-v5-16434) - Through description on some of the exciting new features in PowerShell version 5.0.
- [PowerShell Open Source Project](https://channel9.msdn.com/series/PowerShell-Open-Source-Project) - Collection of videos thoroughly demonstrate how PowerShell open source project runs on Linux.
- [PowerShell on Linux and Open Source](https://channel9.msdn.com/Blogs/hybrid-it-management/PowerShell-on-Linux-and-Open-Source) - Brief introduction to PowerShell open source project and how it runs on linux.
- [PowerShell](https://channel9.msdn.com/Shows/MsftPowerShell) - This show will include videos talking about the PowerShell automation platform, Desired State Configuration (DSC), infrastructure as code, and related concepts!! These videos are created by Trevor Sullivan, a Microsoft MVP for Windows PowerShell.

## Webserver

- [Flancy ★106 ⏳1Y](toenuff/flancy) - Web microframework for Windows PowerShell.
- [NancyPS ★15](Jaykul/NancyPS) - Nancy, self-hosted in PowerShell, with script method handlers.
- [PoSH Server](http://www.poshserver.net/) - Secure, flexible and lightweight web server to meet your requirements.
- [WebCommander ★121](vmware/webcommander) - Run scripts and view results, in a friendly web GUI or via a web service.

## SharePoint

- [AutoSPInstaller](https://autospinstaller.codeplex.com/) - Automated SharePoint 2010/2013 installation script.
- [Client-side SharePoint](https://sharepointpowershell.codeplex.com/) - API for SharePoint 2010, 2013 and Online.

## SQL Server

- [dbareports](https://dbareports.io) - Gather, store and display your SQL Server estate data.
- [dbatools](https://dbatools.io) - Instance migrations and best practice implementations.

## Misc

- [poke ★25 ⏳1Y](oising/poke) - Crazy cool reflection module for powershell.
  Explore and invoke private APIs like nobody is watching.
  Useful for security research, testing and quick hacks.
- [psInlineProgress ★18 ⏳1Y](gravejester/psInlineProgress) - Write inline progress bars in PowerShell. 
---
<p align="center">
	This list is a copy of <a href="janikvonrotz/awesome-powershell">janikvonrotz/awesome-powershell</a> with ranks
</p>
