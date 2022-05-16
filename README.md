# lzz

Once upon a time, there was a project called *Lazy C++* ("`lzz`"), which allowed C++ programmers to write code without worrying so much about header files. For projects where header files weren't important, this was a big time-saver.

The Lazy C++ project [became unmaintained](https://github.com/mjspncr/lzz3/issues/32) sometime in 2020, but other projects still depend on it. To help people maintain such projects, this repository contains executable binaries of the most recent published version of `lzz` (v2.8.2). Since it is not longer being updated, it may not support newer features of the C++ programming language.

### Downloads

- [Linux, Intel 386](./downloads/lzz_2_8_2_linux.zip?raw=1)
- [Windows, Intel 386](./downloads/lzz_2_8_2_windows.zip?raw=1)
- [Mac, OS X](./downloads/lzz_2_8_2_mac.zip?raw=1)

> To install `lzz`, simply place the executable in your path. The Linux binary was built with g++ 4.4.4 on Slackware 13.1.0. The Windows binary was built using mingw g++ 3.4.5 cross compiler. The Mac binary was built using the g++ Xcode 3.x compiler (i686-apple-darwin10-g++-4.2.1).

### Source code

- [Download source code](./downloads/lzz_2_8_2_src_gen.zip?raw=1)

> To build, type `make -f Makefile.release` in the `lzz_2_8_2_src_gen` directory. This should work on all Unix-like platforms, including Mac OS X.

## Documentation

Documentation can be found on [web.archive.org](http://web.archive.org/web/20200203175114/http://www.lazycplusplus.com/doc.html).

## Attributions

> Lzz is released under the GNU General Public License (GPL).

> Lzz was developed by Mike Spencer.

> Thanks to Alex Wall for providing the binary and Makefile for the Mac!
