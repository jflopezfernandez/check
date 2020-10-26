# TODO
The following are considered bugs in [Check][]. If you have
a fix, please submit a pull request.

Bug fixes are considered more important than feature
requests at the moment. Please check the GitHub issue
tracker before creating a new issue.

## Table of Contents
 * [Documentation](#documentation)
 * [Interface](#interface)
 * [Source Code](#source-code)
 * [Internal Tests](#internal-tests)
 * [Packaging](#packaging)
 * [Website](#website)
 * [Printing and Logging](#printing-and-logging)
 * [Unit Tests](#unit-tests)
 * [Check Internals](#check-internals)

## Documentation
 - [ ] Document [pkg-config][] usage. Note that old macro
 usage is not recommended.
 - [ ] Update tutorial to match with the API changes. (Ex: `TTest*` instead of `TFun`)

## Interface
 - [ ] Modify identifiers to prevent polluting the global
 namespace. Prepend `CHECK_` to all constants, `check_` to
 all exported symbols, and `_check` to all internal
 functions.
 - [ ] Fix `fail()`, which is currently causing some problems.
 - [ ] Deprecate the old API in a nice way.

## Source Code
 - [ ] Add `AC_PROG_CC_C99` in `configure.ac` when autoconf2.60b
 is commonly available.
 - [ ] Add checks in `src/check.h.in` for macro varargs
 support.
 - [ ] Figure out if we need `stamp-h.in`.
 - [ ] Use `AC_CONFIG_MACRO_DIR([m4])` and create an `m4/`
 directory for `check.m4`.
 - [ ] Fix overriding `CFLAGS` in `configure.ac`.

## Internal Tests

## Packaging

## Website

## Printing and Logging

## Unit Tests

## Check Internals

  [Check]: https://github.com/libcheck/check "Check - Github"
  [issue tracker]: https://github.com/libcheck/check/issues
  "Check Issue Tracker - GitHub"
  [pkg-config]: https://www.freedesktop.org/wiki/Software/pkg-config/
  "pkg-config - FreeDesktop.org"
