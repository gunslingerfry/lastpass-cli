# LastPass CLI
#### (c) 2014-2018 LastPass.

Command line interface to [LastPass.com](https://lastpass.com/).

## Operating System Support

`lpass` is designed to run on GNU/Linux, Cygwin and Mac OS X. This is a port for Termux. The upstream lastpass repo is here: https://github.com/lastpass/lastpass-cli

## Dependencies

* [LibreSSL](http://www.libressl.org/) or [OpenSSL](https://www.openssl.org/)
* [libcurl](http://curl.haxx.se/)
* [libxml2](http://xmlsoft.org/)
* [pinentry](https://www.gnupg.org/related_software/pinentry/index.en.html) (optional)
* [Termux:API](https://termux.com/add-on-api.html) for clipboard support (optional)

## Termux

This fork of the lastpass-cli repo is tweaked to install on the very awesome Termux Android emulator https://termux.com

## Building

    $ make

Under the covers, make invokes cmake in a build directory; you may also use
cmake directly if you need more control over the build process.

## Installing

    $ make install

## Running

If you've installed it:

    $ lpass

Otherwise, from the build directory:

    $ ./lpass

## Documentation

The lastpass-cli documentation is built using asciidoc which is not available in Termux. For documentation refer to the generated man page by Lastpass: https://lastpass.github.io/lastpass-cli/lpass.1.html
