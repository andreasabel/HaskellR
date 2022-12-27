# The HaskellR project

![Continuous integration](https://github.com/tweag/HaskellR/workflows/Continuous%20integration/badge.svg?branch=master)

* Website: https://tweag.github.io/HaskellR
* Mailing list: [Google Groups](https://groups.google.com/group/haskellr)

The HaskellR project provides an environment for efficiently
processing data using Haskell or R code, interchangeably. HaskellR
allows Haskell functions to seamlessly call R functions and *vice
versa*. It provides the Haskell programmer with the full breadth of
existing R libraries and extensions for numerical computation,
statistical analysis and machine learning.

## Getting Started & Documentation

All documentation is available on the
[HaskellR website](https://tweag.github.io/HaskellR).

## Developing HaskellR

This project uses Stack. See the [stack documentation][stack-docs] for
further information on how to build, run tests and benchmarks, or
build the API documentation. You can do all of that at once with

```
$ stack build --test --haddock --bench
```

Optionally, pass in the `--nix` flag to all commands if you have the
[Nix][nix] package manager installed. Nix can populate a *local* build
environment including all necessary system dependencies without
touching your global filesystem. Use it as a cross-platform
alternative to Docker.

[nix]: http://nixos.org/nix
[stack-docs]: https://docs.haskellstack.org/en/stable/GUIDE/

## License

Copyright (c) 2013-2015 Amgen, Inc.
Copyright (c) 2015-2022 Tweag I/O Limited.

All rights reserved.

HaskellR is free software, and may be redistributed under the terms
specified in the [LICENSE](LICENSE) file.
