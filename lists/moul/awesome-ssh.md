<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="https://github.com/moul/awesome-ssh">https://github.com/moul/awesome-ssh</a> with ranks
</p>
---
# Awesome SSH [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)

> A curated list of *SSH* [apps](#apps), [libraries](#libraries) and [resources](#resources).

<h2 align="center"><img src="https://raw.githubusercontent.com/moul/awesome-ssh/master/logo.jpg" width="400" /></h2>

Inspired by the [awesome ★57421](https://github.com/sindresorhus/awesome) list thing.

Please read the [contribution guidelines](https://github.com/moul/awesome-ssh/blob/master/CONTRIBUTING.md) if you want to contribute.

**Check out my [blog](http://manfredtouron.tumblr.com) 🦄 or say *hi* on [Twitter](https://twitter.com/moul).**

## Table of Contents

- [Apps](#apps)
  - [`.ssh/config`](#sshconfig)
  - [Tools using the *SSH* protocol](#tools-using-the-ssh-protocol)
  - [Servers](#servers)
  - [Network](#network)
  - [Multiplexers](#multiplexers)
  - [SSH Keys / Authentication](#ssh-keys--authentication)
  - [SSH agent](#ssh-agent)
  - [Tools](#tools)
  - [Automation](#automation)
  - [Web](#web)
  - [Testing / Honeypots](#testing--honeypots)
  - [Alternatives to SSH](#alternatives-to-ssh)
- [Libraries](#libraries)
- [Resources](#resources)
  - [Tutorials](#tutorials)
  - [Security](#security)
  - [Documentation](#documentation)
  - [Community](#community)

## Apps

### `.ssh/config`

* [`assh` a.k.a `advanced-ssh-config`](https://github.com/moul/advanced-ssh-config) [![stars](https://img.shields.io/github/stars/moul/advanced-ssh-config.svg?style=social&label=stars)](https://github.com/moul/advanced-ssh-config) - Transparent wrapper (ProxyCommand) that adds regex, aliases, gateways, includes, dynamic hostnames to *SSH* and `ssh-config`.
* [storm](https://github.com/emre/storm) [![stars](https://img.shields.io/github/stars/emre/storm.svg?style=social&label=stars) ★2798](https://github.com/emre/storm) - Manage your *SSH* like a boss.
* [ansible-ssh-config](https://github.com/gaqzi/ansible-ssh-config) [![stars](https://img.shields.io/github/stars/gaqzi/ansible-ssh-config.svg?style=social&label=stars) ★68](https://github.com/gaqzi/ansible-ssh-config) - Letting *Ansible* manage `ssh_config`.
* [ec2ssh](https://github.com/mirakui/ec2ssh) [![stars](https://img.shields.io/github/stars/mirakui/ec2ssh.svg?style=social&label=stars) ★185](https://github.com/mirakui/ec2ssh) - A `ssh_config` manager for *AWS EC2*.
* [ssh-config](https://github.com/dbrady/ssh-config) [![stars](https://img.shields.io/github/stars/dbrady/ssh-config.svg?style=social&label=stars) ★73 ⏳1Y](https://github.com/dbrady/ssh-config) - A tool to help manage your `.ssh/config` file.

### Tools using the *SSH* protocol

* [scp](http://linux.die.net/man/1/scp) - Secure remote file copy utility over *SSH*.
* [rsync](https://rsync.samba.org) - Fast incremental transfer utility that supports *SSH*.
* [sftp](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol) - File transfer protocol over *SSH*.
* [curl](http://curl.haxx.se) - Command line tool and library to transfer data (support `sftp`).

### Servers

* [ssh2docker](https://github.com/moul/ssh2docker) [![stars](https://img.shields.io/github/stars/moul/ssh2docker.svg?style=social&label=stars) ★72](https://github.com/moul/ssh2docker) - *SSH* server to Docker containers.
* [whosthere](https://github.com/FiloSottile/whosthere) [![stars](https://img.shields.io/github/stars/FiloSottile/whosthere.svg?style=social&label=stars) ★1178 ⏳1Y](https://github.com/FiloSottile/whosthere) - A *SSH* server that knows who you are. `$ ssh whoami.filippo.io`.
* [sshfront](https://github.com/gliderlabs/sshfront) [![stars](https://img.shields.io/github/stars/gliderlabs/sshfront.svg?style=social&label=stars) ★171](https://github.com/gliderlabs/sshfront) - Programmable *SSH* frontend.
* [ssh-chat](https://github.com/shazow/ssh-chat) [![stars](https://img.shields.io/github/stars/shazow/ssh-chat.svg?style=social&label=stars) ★2792](https://github.com/shazow/ssh-chat) - Chat over *SSH*.
* [sshcommand](https://github.com/dokku/sshcommand) [![stars](https://img.shields.io/github/stars/dokku/sshcommand.svg?style=social&label=stars) ★276](https://github.com/dokku/sshcommand) - Turn *SSH* into a thin client specifically for your app.
* [sshmuxd](https://github.com/joushou/sshmuxd) [![stars](https://img.shields.io/github/stars/joushou/sshmuxd.svg?style=social&label=stars) ★679](https://github.com/joushou/sshmuxd) - `sshmux` frontend.
* [x84](https://github.com/jquast/x84) [![stars](https://img.shields.io/github/stars/jquast/x84.svg?style=social&label=stars) ★264](https://github.com/jquast/x84) - A *python* `telnet`/`ssh` server for modern *UTF-8* and classic *cp437* network virtual terminals. In spirit of classic software such as *ami/x*, *teleguard*, *renegade*, *iniquity*.
* [teleport](https://github.com/gravitational/teleport) [![stars](https://img.shields.io/github/stars/gravitational/teleport.svg?style=social&label=stars) ★4883](https://github.com/gravitational/teleport) - Modern *SSH* server for clusters and teams.

### Network

* [Mosh](https://mosh.mit.edu) - The mobile shell.
* [sshfs](https://github.com/libfuse/sshfs) [![stars](https://img.shields.io/github/stars/libfuse/sshfs.svg?style=social&label=stars) ★713](https://github.com/libfuse/sshfs) - Filesystem client based on the *SSH* File Transfer Protocol.
* [ngrok](https://github.com/inconshreveable/ngrok) [![stars](https://img.shields.io/github/stars/inconshreveable/ngrok.svg?style=social&label=stars) ★9737](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost.
* [localtunnel](https://github.com/progrium/localtunnel) [![stars](https://img.shields.io/github/stars/progrium/localtunnel.svg?style=social&label=stars) ★2970 ⏳2Y](https://github.com/progrium/localtunnel) - Expose localhost servers to the Internet.
* [sshuttle](https://github.com/apenwarr/sshuttle) [![stars](https://img.shields.io/github/stars/apenwarr/sshuttle.svg?style=social&label=stars) ★7993](https://github.com/apenwarr/sshuttle) - Transparent proxy server that works as a poor man's *VPN*. Forwards over `ssh`. Doesn't require admin. Works with *Linux* and *MacOS*. Supports *DNS tunneling*.
* [sshttp](https://github.com/stealth/sshttp) [![stars](https://img.shields.io/github/stars/stealth/sshttp.svg?style=social&label=stars) ★427](https://github.com/stealth/sshttp) - *SSH*/*HTTP(S)* multiplexer. Run a webserver and a `sshd` on the same port w/o changes.
* [switcher](https://github.com/jamescun/switcher) [![stars](https://img.shields.io/github/stars/jamescun/switcher.svg?style=social&label=stars)](https://github.com/jamescun/switcher) - Run *SSH* and *HTTP(S)* on the same port.
* [sslh](https://github.com/yrutschle/sslh) [![stars](https://img.shields.io/github/stars/yrutschle/sslh.svg?style=social&label=stars)](https://github.com/yrutschle/sslh) - Applicative Protocol Multiplexer (i.e: *SSH* + *HTTPS*).
* [tund](https://github.com/aphyr/tund) [![stars](https://img.shields.io/github/stars/aphyr/tund.svg?style=social&label=stars) ★335 ⏳1Y](https://github.com/aphyr/tund) - *SSH* reverse tunnel daemon.
* [autossh](http://www.harding.motd.ca/autossh/) - Automatically respawn *SSH* session after network interruption.
* [wssh](https://github.com/aluzzardi/wssh) [![stars](https://img.shields.io/github/stars/aluzzardi/wssh.svg?style=social&label=stars) ★967](https://github.com/aluzzardi/wssh) - *SSH* to WebSockets Bridge.
* [docker-volume-sshfs](https://github.com/vieux/docker-volume-sshfs) [![stars](https://img.shields.io/github/stars/vieux/docker-volume-sshfs.svg?style=social&label=stars) ★114](https://github.com/vieux/docker-volume-sshfs) - `sshfs` docker volume plugin.

### Multiplexers

* [tmux](https://tmux.github.io) - Terminal multiplexer.
* [clusterssh](https://github.com/duncs/clusterssh) [![stars](https://img.shields.io/github/stars/duncs/clusterssh.svg?style=social&label=stars) ★381](https://github.com/duncs/clusterssh) - Cluster admin via *SSH*.
* [tmux-cssh](https://github.com/dennishafemann/tmux-cssh) [![stars](https://img.shields.io/github/stars/dennishafemann/tmux-cssh.svg?style=social&label=stars) ★333](https://github.com/dennishafemann/tmux-cssh) - `tmux` with a *ClusterSSH*-like behavior.
* [tm](https://github.com/Ganneff/tm) [![stars](https://img.shields.io/github/stars/Ganneff/tm.svg?style=social&label=stars) ★25](https://github.com/Ganneff/tm) - `tmux` manager / helper.
* [i2cssh](https://github.com/wouterdebie/i2cssh) [![stars](https://img.shields.io/github/stars/wouterdebie/i2cssh.svg?style=social&label=stars) ★316](https://github.com/wouterdebie/i2cssh) - `csshX` like *SSH* tool for *iTerm2*.
* [ClusterSSH](http://sourceforge.net/projects/clusterssh/) - Controls a number of `xterm` windows via a single graphical console.

### *SSH* keys / Authentication

* [authy-ssh](https://github.com/authy/authy-ssh) [![stars](https://img.shields.io/github/stars/authy/authy-ssh.svg?style=social&label=stars) ★724](https://github.com/authy/authy-ssh) - Easy *two-factor* authentication for *SSH* servers.
* [github-auth](https://github.com/chrishunt/github-auth) [![stars](https://img.shields.io/github/stars/chrishunt/github-auth.svg?style=social&label=stars) ★356](https://github.com/chrishunt/github-auth) - *SSH* key management for GitHub users.
* [cipherhub](https://github.com/substack/cipherhub) [![stars](https://img.shields.io/github/stars/substack/cipherhub.svg?style=social&label=stars) ★406 ⏳2Y](https://github.com/substack/cipherhub) - Encrypt messages based on *SSH* public keys with easy import from GitHub.
* [Slack notifications](http://www.ryanbrink.com/slack-ssh-session-notifications/) - Guide to setup Slack notifications (can be modified for other services).
* [totp-ssh-fluxer](https://github.com/benjojo/totp-ssh-fluxer) [![stars](https://img.shields.io/github/stars/benjojo/totp-ssh-fluxer.svg?style=social&label=stars) ★650](https://github.com/benjojo/totp-ssh-fluxer) - A way to make sure your `sshd` port changes every 30 seconds.
* [github-keygen](https://github.com/dolmen/github-keygen) [![stars](https://img.shields.io/github/stars/dolmen/github-keygen.svg?style=social&label=stars)](https://github.com/dolmen/github-keygen) - Easy creation of secure *SSH* configuration for your GitHub account(s).

### *SSH* agent

* [ssh-ident](https://github.com/ccontavalli/ssh-ident) [![stars](https://img.shields.io/github/stars/ccontavalli/ssh-ident.svg?style=social&label=stars) ★463](https://github.com/ccontavalli/ssh-ident) - Different agents and different keys for different projects, with `ssh`.
* [oh-my-zsh/plugins/ssh-agent](https://github.com/robbyrussell/oh-my-zsh) [![stars](https://img.shields.io/github/stars/robbyrussell/oh-my-zsh.svg?style=social&label=stars) ★52892](https://github.com/robbyrussell/oh-my-zsh) - `ssh-agent` plugin for `zsh`.

### Tools

* [sshrc](https://github.com/Russell91/sshrc) [![stars](https://img.shields.io/github/stars/Russell91/sshrc.svg?style=social&label=stars) ★3677](https://github.com/Russell91/sshrc) - Bring your `.bashrc`, `.vimrc`, etc. with you when you `ssh`.
* [kyrat](https://github.com/fsquillace/kyrat) [![stars](https://img.shields.io/github/stars/fsquillace/kyrat.svg?style=social&label=stars) ★15](https://github.com/fsquillace/kyrat) - SSH wrapper script that brings your dotfiles always with you on Linux and OSX.

### Automation

* [Ansible](https://github.com/ansible/ansible) [![stars](https://img.shields.io/github/stars/ansible/ansible.svg?style=social&label=stars) ★22836](https://github.com/ansible/ansible) - App deployment, configuration management and orchestration over *SSH*.
* [rtop](https://github.com/rapidloop/rtop) [![stars](https://img.shields.io/github/stars/rapidloop/rtop.svg?style=social&label=stars) ★1531](https://github.com/rapidloop/rtop) - Interactive, remote system monitoring tool based on *SSH*.
* [DSH - Dancer's shell / distributed shell](https://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Wrapper for executing multiple remote shell commands from one command line.
* [parallel-ssh](https://code.google.com/p/parallel-ssh/) - Provides parallel versions of OpenSSH and related tools.
* [SSH Power Tool](https://code.google.com/p/sshpt/) - Execute commands and upload files to many servers simultaneously without using pre-shared keys.

### Web

* [Secure Shell chrome extension](https://chrome.google.com/webstore/detail/secure-shell/pnhechapfaindjhompbnflcldabbghjo?hl=en)
* [GateOne](https://github.com/liftoff/GateOne) [![stars](https://img.shields.io/github/stars/liftoff/GateOne.svg?style=social&label=stars) ★4375](https://github.com/liftoff/GateOne) - HTML5-powered terminal emulator and *SSH* client.
* [KeyBox](https://github.com/skavanagh/KeyBox) [![stars](https://img.shields.io/github/stars/skavanagh/KeyBox.svg?style=social&label=stars) ★1753](https://github.com/skavanagh/KeyBox) - Web-based *SSH* console that centrally manages administrative access to systems.
* [Apache Guacamole](https://guacamole.incubator.apache.org/) - Apache Guacamole is a HTML5 based clientless remote desktop gateway. It supports standard protocols like VNC, RDP, and SSH.

### Testing / Honeypots

* [ssh-hammer](https://github.com/shazow/ssh-hammer) [![stars](https://img.shields.io/github/stars/shazow/ssh-hammer.svg?style=social&label=stars) ★5](https://github.com/shazow/ssh-hammer) - *SSH* load testing tool.
* [kippo](https://github.com/desaster/kippo) [![stars](https://img.shields.io/github/stars/desaster/kippo.svg?style=social&label=stars) ★869](https://github.com/desaster/kippo) - *SSH* Honeypot.
* [cowrie](https://github.com/micheloosterhof/cowrie) [![stars](https://img.shields.io/github/stars/micheloosterhof/cowrie.svg?style=social&label=stars)](https://github.com/micheloosterhof/cowrie) - *SSH* Honeypot (based on kippo).
* [sshmitm](http://linux.die.net/man/8/sshmitm) - *SSH* monkey-in-the-middle.
* [ssh-audit](https://github.com/arthepsy/ssh-audit) [![stars](https://img.shields.io/github/stars/arthepsy/ssh-audit.svg?style=social&label=stars) ★1396](https://github.com/arthepsy/ssh-audit) - A tool for *SSH* server auditing.
* [sshesame](https://github.com/jaksi/sshesame) [![stars](https://img.shields.io/github/stars/jaksi/sshesame.svg?style=social&label=stars) ★760](https://github.com/jaksi/sshesame) - A fake SSH server that lets everyone in and logs their activity.


### Alternatives to *SSH*

* [GoTTY](https://github.com/yudai/gotty) [![stars](https://img.shields.io/github/stars/yudai/gotty.svg?style=social&label=stars) ★7515](https://github.com/yudai/gotty) - Share your terminal as web application.
* [telnet](http://www.telnet.org/htm/faq.htm) - An unencrypted network protocol and an application used to connect to remote computers and issue commands.
* [rsh](https://en.wikipedia.org/wiki/Remote_Shell) - An unencrypted network protocol and application used to connect to remote computers and issue commands.

## Libraries

* C/C++
  * [libssh](https://www.libssh.org) - The *SSH* library.
  * [substack/libssh](https://github.com/substack/libssh) [![stars](https://img.shields.io/github/stars/substack/libssh.svg?style=social&label=stars) ★56](https://github.com/substack/libssh) - Multiplatform C library implementing the SSHv2 and SSHv1 protocol on client and server side.
* Golang
  * [crypto/ssh](https://godoc.org/golang.org/x/crypto/ssh) - Built-in *SSH* client and server library.
  * [sftp](https://github.com/pkg/sftp) [![stars](https://img.shields.io/github/stars/pkg/sftp.svg?style=social&label=stars) ★355](https://github.com/pkg/sftp) - *SFTP* support for the go.crypto/ssh package.
  * [go-sshkit](https://github.com/shazow/go-sshkit) [![stars](https://img.shields.io/github/stars/shazow/go-sshkit.svg?style=social&label=stars) ★9 ⏳1Y](https://github.com/shazow/go-sshkit) - Toolkit for building *SSH* servers and clients in Go.
  * [Socker](https://github.com/cosiner/socker) [![stars](https://img.shields.io/github/stars/cosiner/socker.svg?style=social&label=stars) ★179](https://github.com/cosiner/socker) - Library for Go to simplify the use of *SSH*.
* Java
  * [jsch](http://www.jcraft.com/jsch/) - Pure *java*, *BSD* licensed, *SSH2* client library.
* Javascript/Node.js
  * [ssh2](https://github.com/mscdex/ssh2) [![stars](https://img.shields.io/github/stars/mscdex/ssh2.svg?style=social&label=stars) ★2466](https://github.com/mscdex/ssh2) - *SSH2* client and server modules written in pure *JavaScript* for *node.js*.
* Python
  * [paramiko](https://github.com/paramiko/paramiko) [![stars](https://img.shields.io/github/stars/paramiko/paramiko.svg?style=social&label=stars) ★3339](https://github.com/paramiko/paramiko) - Native *Python* *SSHv2* protocol library.
* Ruby
  * [net-ssh](https://github.com/net-ssh/net-ssh) [![stars](https://img.shields.io/github/stars/net-ssh/net-ssh.svg?style=social&label=stars)](https://github.com/net-ssh/net-ssh) - Pure *Ruby* implementation of an *SSH* (protocol 2) client.

## Resources

### Tutorials

* [How to use *SSH* to Connect to a Remote Server](https://www.digitalocean.com/community/tutorials/how-to-use-ssh-to-connect-to-a-remote-server-in-ubuntu)
* [Best practices](https://blog.0xbadc0de.be/archives/300)
* [Granting Temporary Access to Your Servers (Using Signed *SSH* Keys)](http://linux-audit.com/granting-temporary-access-to-servers-using-signed-ssh-keys/)
* [How to SSH login without a password](https://www.rosehosting.com/blog/ssh-login-without-password-using-ssh-keys/)

### Security

* [01/14/2016](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2016-0777) - Integer Overflow `CVE 2016 077[7-8]`.
* [Security/Guidelines/OpenSSH - MozillaWiki](https://wiki.mozilla.org/Security/Guidelines/OpenSSH) - `sshd\_config` for `6.7+`, `5.3`.
* [Applied-Crypto-Hardening](https://github.com/BetterCrypto/Applied-Crypto-Hardening) [![stars](https://img.shields.io/github/stars/BetterCrypto/Applied-Crypto-Hardening.svg?style=social&label=stars) ★564](https://github.com/BetterCrypto/Applied-Crypto-Hardening) - `sshd\_config` for `6.X`

### Documentation

* [man page](http://linux.die.net/man/1/ssh)
* [Specifications (OpenSSH)](http://www.openssh.com/specs.html)
* [Wikipedia article](https://en.wikipedia.org/wiki/Secure_Shell)

### Community

* [StackOverflow](http://stackoverflow.com/questions/tagged/ssh)
* [ServerFault](http://serverfault.com/questions/tagged/ssh)

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Manfred Touron](https://github.com/moul) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/moul/awesome-ssh">https://github.com/moul/awesome-ssh</a> with ranks
</p>