<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="sobolevn/awesome-cryptography">sobolevn/awesome-cryptography</a> with ranks
</p>
---
# Awesome Cryptography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

[![Build Status](https://travis-ci.org/sobolevn/awesome-cryptography.svg)](https://travis-ci.org/sobolevn/awesome-cryptography) [![Join the chat at https://gitter.im/sobolevn/awesome-cryptography](https://badges.gitter.im/sobolevn/awesome-cryptography.svg)](https://gitter.im/sobolevn/awesome-cryptography?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Follow us on twitter](https://img.shields.io/twitter/follow/awe_crypto_bot.svg?style=social&maxAge=0)](https://twitter.com/awe_crypto_bot)

A curated list of cryptography resources and links.

## Contents

<!--lint disable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- [Theory](#theory)
  - [Algorithms](#algorithms)
    - [Symmetric encryption](#symmetric-encryption)
    - [Asymmetric encryption](#asymmetric-encryption)
    - [Hash functions](#hash-functions)
  - [Articles](#articles)
  - [Books](#books)
  - [Courses](#courses)
- [Tools](#tools)
  - [Standalone](#standalone)
  - [Plugins](#plugins)
    - [Git](#git)
- [Frameworks and Libs](#frameworks-and-libs)
  - [C](#c)
  - [C#](#c-sharp)
  - [C++](#cpp)
  - [Clojure](#clojure)
  - [Common Lisp](#common-lisp)
  - [Delphi](#delphi)
  - [Elixir](#elixir)
  - [Erlang](#erlang)
  - [Golang](#go)
  - [Haskell](#haskell)
  - [Haxe](#haxe)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [Julia](#julia)
  - [Lua](#lua)
  - [Objective-C](#objective-c)
  - [PHP](#php)
  - [Python](#python)
  - [R](#r)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Scala](#scala)
  - [Swift](#swift)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Mailing lists](#mailing-lists)
  - [Web-tools](#web-tools)
  - [Web-sites](#web-sites)
- [Contributing](#contributing)
- [License](#license)

<!--lint enable no-missing-blank-lines alphabetize-lists list-item-punctuation-->

- - -

## Theory

### Algorithms

#### Symmetric encryption

- [3DES](https://en.wikipedia.org/wiki/Triple_DES) - Symmetric-key block cipher (or Triple Data Encryption Algorithm (TDEA or Triple DEA), which applies the Data Encryption Standard (DES) cipher algorithm three times to each data block.
- [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) - Symmetric-key block cipher algorithm and U.S. government standard for secure and classified data encryption and decryption (also known as Rijndael).
- [Blowfish](https://en.wikipedia.org/wiki/Blowfish_(cipher)) - Symmetric-key block cipher, designed in 1993 by Bruce Schneier. Notable features of the design include key-dependent S-boxes and a highly complex key schedule.

#### Asymmetric encryption

- [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) - One of the first practical public-key cryptosystems and is widely used for secure data transmission. In RSA, this asymmetry is based on the practical difficulty of factoring the product of two large prime numbers, the factoring problem.

#### Hash functions

- [MD5](https://en.wikipedia.org/wiki/MD5) - Widely used hash function producing a 128-bit hash value. MD5 was initially designed to be used as a cryptographic hash function, but it has been found to suffer from extensive vulnerabilities. It can still be used as a checksum to verify data integrity, but only against unintentional corruption.
- [SHA1](https://en.wikipedia.org/wiki/SHA-1) -  Cryptographic hash function designed by the NSA. SHA-1 produces a 160-bit hash value known as a message digest. SHA-1 is no longer considered secure against well-funded opponents.
- [SHA2](https://en.wikipedia.org/wiki/SHA-2) - Set of hash functions designed by the NSA. SHA-256 and SHA-512 are novel hash functions computed with 32-bit and 64-bit words, respectively. They use different shift amounts and additive constants, but their structures are otherwise virtually identical, differing only in the number of rounds.

### Articles

- [How to Generate Secure Random Numbers in Various Programming Languages](https://paragonie.com/blog/2016/05/how-generate-secure-random-numbers-in-various-programming-languages).
- [Secure Account Recovery Made Simple](https://paragonie.com/blog/2016/09/untangling-forget-me-knot-secure-account-recovery-made-simple).

### Books

- [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/) - The book covers many constructions for different tasks in cryptography.
- [An Introduction to Mathematical Cryptography](http://www.math.brown.edu/~jhs/MathCryptoHome.html) - Introduction to modern cryptography.
- [Crypto101](https://www.crypto101.io/) - Crypto 101 is an introductory course on cryptography.
- [Cryptography Engineering](https://www.schneier.com/books/cryptography_engineering/) - Learn to build cryptographic protocols that work in the real world.
- [Handbook of Applied Cryptography](http://cacr.uwaterloo.ca/hac/index.html) - This book is intended as a reference for professional cryptographers.
- [Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html) - Introductory-level treatment of cryptography written from a modern, computer science perspective.
- [OpenSSL Cookbook](https://www.feistyduck.com/library/openssl-cookbook/) - The book about OpenSSL.
- [Security Engineering](http://www.cl.cam.ac.uk/~rja14/book.html) - There is an extraordinary textbook written by Ross Anderson, professor of computer security at University of Cambridge.
- [The Cryptoparty Handbook](https://unglue.it/work/141611/) - This book provides a comprehensive guide to the various topics of the computer and internet security.
- [Understanding Cryptography](http://www.crypto-textbook.com/) - Often overlooked, this book is a boon for beginners to the field. It contains plenty of exercises at the end of each chapter, aimed at reinforcing concepts and cementing ideas.

### Courses

- [Applied Cryptography](https://www.udacity.com/course/applied-cryptography--cs387) - Cryptography is present in everyday life, from paying with a credit card to using the telephone. Learn all about making and breaking puzzles in computing.
- [Crypto Strikes Back!](https://www.youtube.com/watch?v=ySQl0NhW1J0) - This talk will cover crypto vulnerabilities in widely-deployed systems and how the smallest oversight resulted in catastrophe.
- [Cryptography](https://www.coursera.org/learn/cryptography) - A practical oriented course in Cryptography by University of Maryland College Park.
- [Cryptography - Stanford University](http://online.stanford.edu/course/cryptography) - This course explains the inner workings of cryptographic primitives and how to correctly use them. Students will learn how to reason about the security of cryptographic constructions and how to apply this knowledge to real-world applications.
- [Cryptography I](https://www.coursera.org/learn/crypto) - The course begins with a detailed discussion of how two parties who have a shared secret key can communicate securely when a powerful adversary eavesdrops and tampers with traffic. We will examine many deployed protocols and analyze mistakes in existing systems.
- [Cybrary Cryptography](https://www.cybrary.it/course/cryptography/) - This online course we will cover how cryptography is the cornerstone of security, and how through its use of different encryption methods, such as ciphers, and public or private keys, you can protect private or sensitive information from unauthorized access.
- [Journey into cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) - The course of cryptography by Khan Academy.
- [Practical Aspects of Modern Cryptography](http://courses.cs.washington.edu/courses/csep590/06wi/) - Practical Aspects of Modern Cryptography, Winter 2006 University of Washington CSE.
- [Theory and Practice of Cryptography](https://www.youtube.com/watch?v=ZDnShu5V99s) - Introduction to Modern Cryptography, Using Cryptography in Practice and at Google, Proofs of Security and Security Definitions and A Special Topic in Cryptography.

## Tools

### Standalone

- [Bcrypt](http://bcrypt.sourceforge.net/) - Cross-platform file encryption utility.
- [blackbox ★3396](StackExchange/blackbox) - safely store secrets in Git/Mercurial/Subversion.
- [certbot ★18596](certbot/certbot) - Previously the Let's Encrypt Client, is EFF's tool to obtain certs from Let's Encrypt, and (optionally) auto-enable HTTPS on your server. It can also act as a client for any other CA that uses the ACME protocol.
- [cryptomator ★1358](cryptomator/cryptomator) - Multi-platform transparent client-side encryption of your files in the cloud.
- [gpg](https://www.gnupg.org/) - Complete and free implementation of the OpenPGP standard. It allows to encrypt and sign your data and communication, features a versatile key management system. GnuPG is a command line tool with features for easy integration with other applications.
- [ironssh](https://ironcorelabs.com/products/ironsftp) - End-to-end encrypt transferred files using sftp/scp and selectively share with others. Automatic key management works with any SSH server. Encrypted files are gpg compatible.
- [Nipe ★196](GouveaHeitor/nipe) - Nipe is a script to make Tor Network your default gateway. 

### Plugins

#### Git

- [git-crypt ★2193](AGWA/git-crypt) - Transparent file encryption in git.
- [git-secret](https://sobolevn.github.io/git-secret/) - Bash-tool to store your private data inside a git repository.

## Frameworks and Libs

### C

- [crypto-algorithms ★336](B-Con/crypto-algorithms) - Basic implementations of standard cryptography algorithms, like AES and SHA-1.
- [libgcrypt](http://directory.fsf.org/wiki/Libgcrypt) - Cryptographic library developed as a separated module of GnuPG.
- [libsodium ★4184](jedisct1/libsodium) - Modern and easy-to-use crypto library.
- [libtomcrypt ★496](libtom/libtomcrypt) - Fairly comprehensive, modular and portable cryptographic toolkit.
- [monocypher](http://loup-vaillant.fr/projects/monocypher/) - small, portable, easy to use crypto library inspired by libsodium and TweetNaCl.
- [NaCl](https://nacl.cr.yp.to/) - High-speed library for network communication, encryption, decryption, signatures, etc.
- [OpenSSL ★4780](openssl/openssl) - TLS/SSL and crypto library.
- [PolarSSL](https://tls.mbed.org/) - PolarSSL makes it trivially easy for developers to include cryptographic and SSL/TLS capabilities in their (embedded) products, facilitating this functionality with a minimal coding footprint.
- [RHash ★117](rhash/RHash) - Great utility for computing hash sums.
- [tiny-AES128-C ★554](kokke/tiny-AES128-C) - Small portable AES128 in C.
- [wolfSSL ★230](wolfSSL/wolfssl) - Small, fast, portable implementation of TLS/SSL for embedded devices to the cloud.
- [xxHash ★1336](Cyan4973/xxHash) - Extremely fast hash algorithm.

### C++

- [Botan](https://botan.randombit.net/) - Cryptography library written in `C++11`.
- [cryptopp ★625](weidai11/cryptopp) - Crypto++ Library is a free C++ class library of cryptographic schemes.
- [HElib ★1282](shaih/HElib) - Software library that implements homomorphic encryption (HE).
- [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - Low-level cryptographic library.
- [s2n ★2806](awslabs/s2n) - Implementation of the TLS/SSL protocols.

### C-sharp

- [Bouncy Castle](https://bouncycastle.org/csharp/index.html) - All-purpose cryptographic library.
- [libsodium-net ★208](adamcaudill/libsodium-net) - Secure cryptographic library, port of libsodium for .NET.
- [PCLCrypto ★151](AArnott/PCLCrypto) - Provides cryptographic APIs over algorithms implemented by the platform, including exposing them to portable libraries.
- [SecurityDriven.Inferno ★298](sdrapkin/SecurityDriven.Inferno) - .NET crypto done right.
- [StreamCryptor ★53](bitbeans/StreamCryptor) - Stream encryption & decryption with libsodium and protobuf.

### Clojure

- [buddy-core](https://funcool.github.io/buddy-core/latest/) - Cryptographic Api.
- [pandect ★170](xsc/pandect) - Fast and easy-to-use Message Digest, Checksum and HMAC library for Clojure.

### Common Lisp

- [crypto-shortcuts ★10](Shinmera/crypto-shortcuts) - Collection of common cryptography functions.
- [ironclad](http://method-combination.net/lisp/ironclad/) - Collection of common crypto shortcuts.
- [trivial-ssh ★14](eudoxia0/trivial-ssh) - SSH client library for Common Lisp (Built on libssh2).

### Delphi

- [DelphiEncryptionCompendium](https://github.com/winkelsdorf/DelphiEncryptionCompendium/releases) - Cryptographic library for Delphi.
- [LockBox](https://sourceforge.net/projects/tplockbox/) - LockBox 3 is a Delphi library for cryptography.
- [SynCrypto](https://github.com/synopse/mORMot/blob/master/SynCrypto.pas) - Fast cryptographic routines (hashing and cypher), implementing AES, XOR, RC4, ADLER32, MD5, SHA1, SHA256 algorithms, optimized for speed.
- [TForge](https://bitbucket.org/sergworks/tforge) - TForge is open-source crypto library written in Delphi, compatible with FPC.

### Elixir

- [cipher ★19](rubencaro/cipher) - Elixir crypto library to encrypt/decrypt arbitrary binaries.
- [cloak ★128](danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.
- [comeonin](https://github.com/elixircnx/comeonin) - Password authorization (bcrypt) library for Elixir.
- [elixir-rsa ★13 ⏳2Y](trapped/elixir-rsa) - `:public_key` cryptography wrapper for Elixir.
- [elixir_tea ★1 ⏳2Y](keichan34/elixir_tea) - TEA implementation in Elixir.
- [ex_crypto ★28](ntrepid8/ex_crypto) - Elixir wrapper for Erlang `:crypto` and `:public_key` modules. Provides sensible defaults for many crypto functions to make them easier to use.
- [exgpg ★6 ⏳1Y](rozap/exgpg) - Use gpg from Elixir.
- [pot ★38](yuce/pot) - Erlang library for generating one time passwords compatible with Google Authenticator.
- [siphash-elixir ★7](zackehh/siphash-elixir) - Elixir implementation of the SipHash hash family.

### Erlang

- [crypto](http://erlang.org/doc/apps/crypto/) - Functions for computation of message digests, and functions for encryption and decryption.
- [public_key](http://erlang.org/doc/man/public_key.html) - Provides functions to handle public-key infrastructure.

### Go

- [crypto](https://golang.org/pkg/crypto/) - Official Website Resources.
- [cryptoballot ★103](cryptoballot/cryptoballot) - Cryptographically secure online voting.
- [dedis/crypto](https://github.com/dedis/crypto) - Advanced crypto library for the Go language.
- [dkeyczar ★101 ⏳1Y](dgryski/dkeyczar) - Port of Google's Keyczar cryptography library to Go.
- [gocrypto ★85 ⏳2Y](kisom/gocrypto) - Example source code for the Practical Crypto with Go book.

### Haskell

- [Crypto](http://hackage.haskell.org/packages/#cat:Crypto) - Collaborative Hackage list.
- [Cryptography](http://hackage.haskell.org/packages/#cat:Cryptography) - Collaborative Hackage list.
- [Cryptography & Hashing](https://wiki.haskell.org/Applications_and_libraries/Cryptography) - Official Website of Haskell.
- [cryptol ★598](GaloisInc/cryptol) - The Language of Cryptography.
- [Cryptonite](https://hackage.haskell.org/package/cryptonite) - Haskell repository of cryptographic primitives.
- [HsOpenSSL](https://github.com/phonohawk/HsOpenSSL) - OpenSSL binding for Haskel.
- [scrypt ★11 ⏳1Y](informatikr/scrypt) - Haskell bindings to Colin Percival's scrypt implementation.

### Haxe

- [haxe-crypto](http://lib.haxe.org/p/haxe-crypto/) - Haxe Cryptography Library.

### JavaScript

- [asmCrypto ★334](vibornoff/asmcrypto.js) - JavaScript implementation of popular cryptographic utilities with performance in mind.
- [bcrypt-nodejs ★470](shaneGirish/bcrypt-nodejs) - Native implementation of bcrypt for NodeJS.
- [cifre](https://github.com/openpeer/cifre) - Fast crypto toolkit for modern client-side JavaScript.
- [closure-library](https://github.com/google/closure-library/tree/master/closure/goog/crypt) - Google's common JavaScript library.
- [cryptico ★670](wwwtyro/cryptico) - Easy-to-use encryption system utilizing RSA and AES for javascript.
- [crypto-js ★2096](brix/crypto-js) - JavaScript library of crypto standards.
- [cryptojs ★212 ⏳4Y](gwjjeff/cryptojs) - Provide standard and secure cryptographic algorithms for NodeJS.
- [forge ★1907](digitalbazaar/forge) - Native implementation of TLS in Javascript and tools to write crypto-based and network-heavy webapps.
- [javascript-crypto-library ★230 ⏳1Y](clipperz/javascript-crypto-library) - JavaScript Crypto Library provides web developers with an extensive and efficient set of cryptographic functions.
- [js-nacl ★363](tonyg/js-nacl) - Pure-Javascript High-level API to Emscripten-compiled libsodium routines.
- [jsencrypt ★1414](travist/jsencrypt) - Javascript library to perform OpenSSL RSA Encryption, Decryption, and Key Generation.
- [JShashes ★329](h2non/jshashes) - Fast and dependency-free cryptographic hashing library for node.js and browsers (supports MD5, SHA1, SHA256, SHA512, RIPEMD, HMAC).
- [jsrsasign ★1080](kjur/jsrsasign) - The 'jsrsasign' (RSA-Sign JavaScript Library) is an opensource free cryptography library supporting RSA/RSAPSS/ECDSA/DSA signing/validation.
- [libsodium.js ★238](jedisct1/libsodium.js) - libsodium compiled to pure JavaScript, with convenient wrappers.
- [node.bcrypt.js](https://github.com/ncb000gt/node.bcrypt.js) - bcrypt for NodeJS.
- [OpenPGP.js ★2556](openpgpjs/openpgpjs) - OpenPGP implementation for JavaScript.
- [PolyCrypt ★259 ⏳2Y](polycrypt/polycrypt) - Pure JS implementation of the WebCrypto API.
- [rusha ★202](srijs/rusha) - High-performance pure-javascript SHA1 implementation suitable for large binary data, reaching up to half the native speed.
- [sjcl ★4430](bitwiseshiftleft/sjcl) - Stanford Javascript Crypto Library.
- [URSA ★463](quartzjer/ursa) - RSA public/private key OpenSSL bindings for Node.

### Java

- [Apache Shiro](http://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
- [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library. JCA provider, wide range of functions from basic helpers to PGP/SMIME operations.
- [Flexiprovider](http://www.flexiprovider.de/) - Powerful toolkit for the Java Cryptography Architecture.
- [Google Keyczar ★876](google/keyczar) - Easy to use, yet safe encryption framework with key versioning.
- [keywhiz ★1721](square/keywhiz) - A system for distributing and managing secrets.
- [pac4j ★871](pac4j/pac4j) - Security engine.
- [scrypt ★287](wg/scrypt) - Pure Java implementation of the scrypt key derivation function and a JNI interface to the C implementations, including the SSE2 optimized version.

### Julia

- [Crypto.jl ★4](danielsuo/Crypto.jl) - Library that wraps OpenSSL, but also has pure Julia implementations for reference.
- [MbedTLS.jl ★7](JuliaWeb/MbedTLS.jl) - Wrapper around the mbed TLS and cryptography C libary.
- [Nettle.jl ★9](staticfloat/Nettle.jl) - Julia wrapper around nettle cryptographic hashing/
encryption library providing MD5, SHA1, SHA2 hashing and HMAC functionality, as well as AES encryption/decryption.
- [SHA.jl ★14](staticfloat/SHA.jl) - Performant, 100% native-julia SHA1, SHA2-{224,256,384,512} implementation.

### Lua

- [lua-lockbox ★203](somesocks/lua-lockbox) - Collection of cryptographic primitives written in pure Lua.
- [LuaCrypto ★63 ⏳1Y](mkottman/luacrypto) - Lua bindings to OpenSSL.

### Objective-C

- [CocoaSecurity ★830](kelp404/CocoaSecurity) - AES, MD5, SHA1, SHA224, SHA256, SHA384, SHA512, Base64, Hex.
- [RNCryptor ★2535](RNCryptor/RNCryptor) - CCCryptor (AES encryption) wrappers for iOS and Mac.
- [Themis ★379](cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption.

### PHP

- [halite](https://paragonie.com/project/halite) - Simple library for encryption using `libsodium`.
- [libsodium-laravel ★15 ⏳1Y](scrothers/libsodium-laravel) - Laravel Package Abstraction using `libsodium`.
- [PHP Encryption ★1168](defuse/php-encryption) - Library for encrypting data with a key or password in PHP.
- [TCrypto ★50](timoh6/TCrypto) - TCrypto is a simple and flexible PHP 5.3+ in-memory key-value storage library.

### Python

- [bcrypt ★295](pyca/bcrypt) - Modern password hashing for your software and your servers.
- [charm ★164](JHUISI/charm) - Framework for rapidly prototyping cryptosystems.
- [cryptography](https://cryptography.io/en/latest/) - Python library which exposes cryptographic recipes and primitives.
- [cryptopy](https://sourceforge.net/projects/cryptopy/) - Pure python implmentation of cryptographic algorithms and applications.
- [hashids ★591](davidaurelio/hashids-python) - Implementation of [hashids](http://hashids.org) in Python.
- [paramiko](http://www.paramiko.org/) - Python implementation of the SSHv2 protocol, providing both client and server functionality.
- [pycryptodome ★170](Legrandin/pycryptodome) - Self-contained Python package of low-level cryptographic primitives.
- [PyElliptic ★88](yann2192/pyelliptic) - Python OpenSSL wrapper. For modern cryptography with ECC, AES, HMAC, Blowfish.
- [pynacl ★363](pyca/pynacl) - Python binding to the Networking and Cryptography (NaCl) library.

### R

- [rscrypt ★12](rstudio/rscrypt) - Package for a collection of scrypt cryptographic functions.

### Ruby

- [bcrypt-ruby ★1158](codahale/bcrypt-ruby) - Ruby binding for the OpenBSD bcrypt() password hashing algorithm, allowing you to easily store a secure hash of your users' passwords.
- [RbNaCl ★640](cryptosphere/rbnacl) - Ruby binding to the Networking and Cryptography (NaCl) library.

### Rust

- [octavo ★116](libOctavo/octavo) - Highly modular & configurable hash & crypto library.
- [ring ★510](briansmith/ring) - Safe, fast, small crypto using Rust & BoringSSL's cryptography primitives.
- [rust-crypto ★575](DaGenix/rust-crypto) - Mostly pure-Rust implementation of various cryptographic algorithms.
- [rust-openssl ★273](sfackler/rust-openssl) - OpenSSL bindings for Rust.
- [rustls ★507](ctz/rustls) - Rustls is a new, modern TLS library written in Rust.
- [sodiumoxide ★211](dnaq/sodiumoxide) - Sodium Oxide: Fast cryptographic library for Rust (bindings to libsodium).
- [suruga ★127 ⏳1Y](klutzy/suruga) - TLS 1.2 implementation in Rust.
- [webpki ★87](briansmith/webpki) - Web PKI TLS X.509 certificate validation in Rust.

### Scala

- [scrypto ★52](input-output-hk/scrypto) - Cryptographic primitives for Scala.

### Swift

- [CryptoSwift ★3770](krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language.
- [IDZSwiftCommonCrypto ★312](iosdevzone/IDZSwiftCommonCrypto) - Wrapper for Apple's [CommonCrypto](https://opensource.apple.com/source/CommonCrypto/) library written in Swift.
- [OpenSSL](https://github.com/Zewo/OpenSSL) - Swift OpenSSL for OS X and Linux.
- [SweetHMAC ★29](jancassio/SweetHMAC) - Tiny and easy to use Swift class to encrypt strings using HMAC algorithms.
- [Swift-Sodium ★148](jedisct1/swift-sodium) - Swift interface to the Sodium library for common crypto operations for iOS and OS X.
- [SwiftSSL ★182 ⏳1Y](SwiftP2P/SwiftSSL) - Elegant crypto toolkit in Swift.

## Resources

### Blogs

- [A Few Thoughts on Cryptographic Engineering](http://blog.cryptographyengineering.com/) - Some random thoughts about crypto.
- [Bristol Cryptography Blog](http://bristolcrypto.blogspot.co.uk/) - Official blog for the University of Bristol cryptography research group. It's a group blog, primarily targeted towards cryptographers and crypto students.
- [Charles Engelke's Blog](https://blog.engelke.com/tag/webcrypto/) - WebCrypto Blog Posts.
- [Root Labs rdist](https://rdist.root.org/) - Nate Lawson and his co-authors write on a variety of topics including hardware implementation, cryptographic timing attacks, DRM, and the Commodore 64.
- [Schneier on security](https://www.schneier.com/) - One of the oldest and most famous security blogs. Bruce covers topics from block cipher cryptanalysis to airport security.

### Mailing lists

- [metzdowd.com](http://www.metzdowd.com/mailman/listinfo/cryptography) - "Cryptography" is a low-noise moderated mailing list devoted to cryptographic technology and its political impact.
- [Modern Crypto](https://moderncrypto.org/) - Forums for discussing modern cryptographic practice.
- [randombit.net](https://lists.randombit.net/mailman/listinfo/cryptography) - List for general discussion of cryptography, particularly the technical aspects.

### Web-tools

- [Cryptolab](http://manansingh.github.io/Cryptolab-Offline/cryptolab.html) - is a set of cryptography related tools.
- [CrypTool](http://www.cryptool-online.org/) - Great variety of ciphers, encryption methods and analysis tools are introduced, often together with illustrated examples.
- [CyberChef](https://gchq.github.io/CyberChef/) - a web app for encryption, encoding, compression, and data analysis.
- [keybase.io](https://keybase.io/) - Keybase maps your identity to your public keys, and vice versa.

### Web-sites

- [Cryptography Stackexchange](http://crypto.stackexchange.com/) - Cryptography Stack Exchange is a question and answer site for software developers, mathematicians and others interested in cryptography.
- [Cryptopals Crypto Challenges](http://cryptopals.com/) - A series of applied cryptography challenges, starting from very basic challenges, such as hex to base 64 challanges, and gradually increasing the difficulty up to abstract algebra.
- [Garykessler Crypto](http://www.garykessler.net/library/crypto.html) - An Overview of Cryptography.
- [IACR](https://www.iacr.org/) - The International Association for Cryptologic Research is a non-profit scientific organization whose purpose is to further research in cryptology and related fields.
- [Learn Cryptography](https://learncryptography.com/) - Dedicated to helping people understand how and why the cryptographic systems they use everyday without realizing work to secure and protect their privacy.
- [Subreddit of Cryptography](https://www.reddit.com/r/cryptography/) - This subreddit is intended for links and discussions surrounding the theory and practice of strong cryptography.
- [WebCryptoAPI](https://www.w3.org/TR/WebCryptoAPI/) - This specification describes a JavaScript API for performing basic cryptographic operations in web applications, such as hashing, signature generation and verification, and encryption and decryption.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/sobolevn/awesome-cryptography/blob/master/CONTRIBUTING.md) first.

## License

`awesome-cryptography` by [@sobolevn](https://github.com/sobolevn)

To the extent possible under law, the person who associated CC0 with
`awesome-cryptography` has waived all copyright and related or neighboring
rights to `awesome-cryptography`.

You should have received a copy of the CC0 legalcode along with this
work.  If not, see [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/).
---
<p align="center">
	This list is a copy of <a href="sobolevn/awesome-cryptography">sobolevn/awesome-cryptography</a> with ranks
</p>
