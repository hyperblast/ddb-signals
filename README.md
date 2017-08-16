Signals support plugin for DeaDBeeF music player
===
This plugin adds support for unix signals to DeaDBeeF music player.

Features:
- Clean shutdown on `SIGTERM` and `SIGINT`.
- Restart player on `SIGHUP`.

[![Build Status](https://travis-ci.org/hyperblast/ddb-signals.svg?branch=master)](https://travis-ci.org/hyperblast/ddb-signals)

How to build
---
`make` will build the plugin file. Make sure you have build tools installed.

How to install
---
`make install` will copy compiled plugin file to `$HOME/.local/lib/deadbeef`.

How to use
---
There are no configuration options. Once plugin is activated it will intercept signals and initiate correct player termination.

License
---
[MIT](LICENSE)
