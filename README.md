LLVM Builds for Qwerty
======================

This repository handles my ~~hacks~~ ingenious engineering for automatically
building LLVM for me on macOS (arm64), Windows (amd64), and GNU/Linux (amd64).

Only the actual Github Actions workflow is in this repository. The scripts used
are in the `ci/` directory of [the Qwerty repository][1].

**To build a new LLVM release,** simply create a new release here in GitHub
with the tag e.g. `v19.1.6` (to build LLVM 19.1.6, for example).

[1]: https://github.com/gt-tinker/qwerty
