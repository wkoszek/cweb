# The CWEB System of Structured Documentation

[![Build Status](https://travis-ci.org/wkoszek/cweb.svg?branch=master)](https://travis-ci.org/wkoszek/cweb)

For the original `README` file refer to [README](README)

This package contains the source code of "The CWEB System of Structured
Documentation", authored by Silvio Levy and Donald E. Knuth modified to
compile with 0 warnings with a modern C compiler (as of August, 2015).

CWEB was originally created in 1987. In 2015 when compiled with GCC/Clang
compiler, it generates tons of warning messages. Version present in this
repository contains source code cleanups letting me to integrate CWEB into
my build infrastructure.

Source code in this repository is based on `cweb.tar.gz` distribution
obtained from:

	ftp://ftp.cs.stanford.edu/pub/cweb/cweb.tar.gz

MD5 checksum of the file

	MD5 (cweb.tar.gz) = 8e488ec9932c117908c92d1c4614cdee

# Continuous integration

To make sure this project doesn't get broken, I configured Travis CI
(http://www.travis-ci.org) system to fetch files from this repository on
every change. In other words: each time I or anybody else will make a change
to this repository, Travis Ci will fetch the source code and try to
recompile the project to make sure everything builds fine

# Copyright

For the native CWEB stuff and their licensing, see CWEB source code files.
Everything that I added is distributed with the same license as the CWEB
system.

# Author

- Wojciech Adam Koszek, [wojciech@koszek.com](mailto:wojciech@koszek.com)
- [http://www.koszek.com](http://www.koszek.com)
