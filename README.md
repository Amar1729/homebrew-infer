# Infer: Homebrew Tap

A custom tap for [infer](https://github.com/facebook/infer) since the formula requires some odd things to build (see [previous attempts for pull requests on core](https://github.com/Homebrew/homebrew-core/pulls?utf8=%E2%9C%93&q=is%3Apr+in%3Atitle+infer)).

This formula provides `infer` built with both C/C++ and Java support.

This formula currently provides prebuilt bottles for Mojave, and uses Homebrew-core's `bintray` for older infer 0.15.0 bottles.

## Installation
```bash
# if running at least Mojave:
$ brew install amar1729/infer/infer
```

## Older Versions
```
# if running Sierra through El Capitan, you can use an older version of infer.
# this is NOT recommended, since 0.15.0 is quite old; it is purely kept for transitionary period and will be removed from this tap soon.
$ brew install amar1729/infer/infer@0.15.0
```
