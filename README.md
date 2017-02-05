Rokid Factory Test Mode(RFTM)
=============================

build status
-------------

| [Linux & Mac OS][travis-ci] | [Windows](#)           |
|-----------------------------|------------------------|
| ![travis-ci-status]         | [To be continue...]    |

[travis-ci]:https://travis-ci.org/ftmdevlopment/rftm
[travis-ci-status]: https://travis-ci.org/ftmdevlopment/rftm.svg?branch=master

quick start
------------

1. ndk-build enviroment setup
  1. [download NDK toolchain package](https://developer.android.com/ndk/downloads/index.html)(I used `r13b`).
  2. uncompress NDK package.
  3. add the uncompressed directory to `PATH`.
2. download source code here
  1. `git clone https://github.com/ftmdevlopment/rftm.git`.
  2. `cd rftm && git submodule update --init --recursive`.
3. ndk-build and run
