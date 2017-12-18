# Awesome MRuby

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome MRuby frameworks, libraries and software.

### Contributing

Please take quick gander at the [contribution guidelines](https://github.com/nsheremet/awesome-mruby/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/nsheremet/awesome-mruby/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome MRuby](#awesome-mruby)
  - [APIs](#apis)
  - [Configuration](#configuration)
  - [Database](#datebase)
  - [Data Structures](#data-structures)
  - [Distributed Systems](#distributed-systems)
  - [Files](#files)
  - [Logging](#logging)
  - [Natural Language Processing](#natural-language-processing)
  - [Networking](#networking)
  - [Parsers](#parsers)
  - [System](#system)
  - [Tasks](#tasks)
  - [Testing](#testing)
  - [Threads](#threads)
  - [Web Frameworks](#web-frameworks)

## APIs

  *Libraries for working with APIs*

* [mruby-zabbix](https://github.com/matsumotory/mruby-zabbix) - Zabbix 2.0 API Client for MRuby.

## Configuration

  *Libraries for configuration, and working with config files*

* [mruby-yaml](https://github.com/hone/mruby-yaml) - libyaml wrapper for YAML Structs. Without File IO support.

## Database

  *Libraries for working with databases*

* [mruby-sqlite](https://github.com/jbreeden/mruby-sqlite) - (Another) SQLite3 mrbgem, aiming for compatability with MRI's sqlite3 gem.
* [mruby-sqlite3](https://github.com/mattn/mruby-sqlite3) - SQLite3 Database.
* [mruby-vedis](https://github.com/matsumotory/mruby-vedis) - Binding vedit for mruby. Vedis is a embeddable datastore.

## Data Structures
  
  *Libs with datastructures*

* [mruby-userdata](https://github.com/matsumotory/mruby-userdata) - When shared mrb_state, you can share userdata objects between one Ruby code and the other.

## Distributed Systems

  *Packages that help with building Distributed Systems.*

* [mruby-wslay](https://github.com/Asmod4n/mruby-wslay) - Wslay is a callback based WebSocket Client and Server library written in C.

## Files

  *Working with files libs*

* [mruby-tempfile](https://github.com/iij/mruby-tempfile) - Tempfile class for mruby (experimental).

## Logging

  *libs for logging*

* [mruby-syslog](https://github.com/iij/mruby-syslog) - Syslog module for mruby.

## Natural Language Processing

  *Libraries for working with human languages*

* [mruby-unicode-display_width](https://github.com/appPlant/mruby-unicode-display_width) - Monospace Unicode character width in MRuby

## Networking

  *Libraries for working with various layers of the network.*

* [mruby-socket](https://github.com/iij/mruby-socket) - Socket library for mruby.
* [mruby-tls](https://github.com/Asmod4n/mruby-tls) - mruby wrapper for libtls from http://www.libressl.org/.

## Parsers

  *Parsing libs*

* [mruby-tinyxml2](https://github.com/h2so5/mruby-tinyxml2) - mruby bindings for TinyXML-2.
* [mruby-uri-parser](https://github.com/Asmod4n/mruby-uri-parser) - URI parser for mruby.

## System

  *Libraries for systems, binding*

* [mruby-tinymt](https://github.com/matsumotory/mruby-tinymt) - rand and srand method with [Tiny Mersenne Twister](http://www.math.sci.hiroshima-u.ac.jp/~m-mat/MT/TINYMT/index.html).
* [mruby-uchardet](https://github.com/take-cheeze/mruby-uchardet/) - mruby binding of mozilla universal charset detector.
* [mruby-uname](https://github.com/matsumotory/mruby-uname) - Uname class, system uname bindings.
* [mruby-unbound](https://github.com/keizo042/mruby-unbound) - libunbound mruby client. `unbound` is DNS cache Server.
* [mruby-uv](https://github.com/mattn/mruby-uv) - interface to libuv for mruby(experimental)
* [mruby-v8](https://github.com/mattn/mruby-v8) - V8 JavaScript Engine.
* [mruby-virtualing](https://github.com/matsumotory/mruby-virtualing) - virtualing is a lightweight virtualization tool for linux processes.
* [mruby-WiringPi](https://github.com/akiray03/mruby-WiringPi) - Binding for Wiring function of the Raspberry Pi.
* [mruby-win32ole](https://github.com/sdottaka/mruby-win32ole) - A port of CRuby's WIN32OLE to mruby.
* [mruby-webkit-3](https://github.com/ppibburr/mruby-webkit-3) - MRuby bindings to mruby-webkit-3.
* [mruby-webkit-1](https://github.com/ppibburr/mruby-webkit-1) - MRuby bindings to mruby-webkit-1.
* [mruby-zlib](https://github.com/jbreeden/mruby-zlib) - Bindings to ZLib for Mruby. Compression Lib.
* [mruby-zmq](https://github.com/Asmod4n/mruby-zmq) - MRuby bindings for [libzmq](https://github.com/zeromq/libzmq).

## Tasks

  *Tasks for MRuby*

* [mruby-updategems](https://github.com/mattn/mruby-updategems) - Rake task to update GEMs.

## Testing

  *Libs for tests*

* [mruby-specinfra](https://github.com/k0kubun/mruby-specinfra) - mruby port of mizzy/specinfra.

## Text Processing

  *Libraries for parsing and manipulating texts.*

* [mruby-terminal-table](https://github.com/appPlant/mruby-terminal-table) - A fast and simple, yet feature rich ASCII table generator for mruby based on terminal-table.
* [mruby-time-strftime](https://github.com/monochromegane/mruby-time-strftime) - Time#strftime for mruby.

## Threads

  *Libraries for working with threads*

* [mruby-thread](https://github.com/mattn/mruby-thread) - Thread Library.
* [mruby-timer-thread](https://github.com/matsumotory/mruby-timer-thread) - Simple Timer Thread.

## Utilities

  *General utilities and tools to make your life easier.*

* [mruby-spdy](https://github.com/matsumotory/mruby-spdy) - SPDY Module for mruby.
* [mruby-statemachine](https://github.com/ascaridol/mruby-statemachine) - a tiny state machine for mruby.
* [mruby-string-crypt](https://github.com/mattn/mruby-string-crypt) - implementation of String#crypt.
* [mruby-string-is-utf8](https://github.com/Asmod4n/mruby-string-is-utf8) - checks if a string is valid utf8.
* [mruby-string-xor](https://github.com/hanachin/mruby-string-xor) - Add String#^(other) method that return XOR of two strings.
* [mruby-stringio](https://github.com/ksss/mruby-stringio) - StringIO class.
* [mruby-sysrandom](https://github.com/Asmod4n/mruby-sysrandom) - Secure random number generation for mruby.

## Web Frameworks

  *Web Frameworks libraries*

* [mruby-simplehttp](https://github.com/nsheremet/mruby-smallhttp) - Small http-client gem for mruby.