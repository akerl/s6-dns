s6-dns
=========

[![Build Status](https://img.shields.io/travis/com/amylum/s6-dns.svg)](https://travis-ci.com/amylum/s6-dns)
[![GitHub release](https://img.shields.io/github/release/amylum/s6-dns.svg)](https://github.com/amylum/s6-dns/releases)
[![ISC Licensed](https://img.shields.io/badge/license-ISC-green.svg)](https://tldrlegal.com/license/-isc-license)

This is my package repo for [s6-dns](http://www.skarnet.org/software/s6-dns/), a set of network librarys and tools by [Laurent Bercot](http://skarnet.org/).

The `upstream/` directory is taken directly from upstream. The rest of the repository is my packaging scripts for compiling a distributable build.

## Usage

To build a new package, update the submodule and run `make`. This launches the docker build container and builds the package.

To start a shell in the build environment for manual actions, run `make manual`.

## License

The s6-dns upstream code is ISC licensed. My packaging code is MIT licensed.

