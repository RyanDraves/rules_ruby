# Ruby Rules for Bazel

## Overview

This repository hosts [Ruby](https://www.ruby-lang.org) language ruleset for [Bazel](https://bazel.build).

The ruleset is known to work with Bazel 5 and 6.

## Getting Started

Pending the first release.

## Toolchains

The following toolchains are known to work and tested.

| Ruby             | Linux | macOS | Windows |
|------------------|-------|-------|---------|
| MRI 3.2          | 🟩    | 🟩    | 🟥      |
| MRI 3.1          | 🟩    | 🟩    | 🟩      |
| MRI 3.0          | 🟩    | 🟩    | 🟩      |
| MRI 2.7          | 🟩    | 🟩    | 🟩      |
| JRuby 9.3        | 🟩    | 🟩    | 🟥      |
| JRuby 9.4        | 🟩    | 🟩    | 🟥      |
| TruffleRuby 22.3 | 🟩    | 🟩    | 🟥      |

On Linux and macOS, [ruby-build](https://github.com/rbenv/ruby-build) is used to
install a toolchain so you can try using any compatbile version, though it's not
guaranteed to work.

On Windows, [RubyInstaller](https://rubyinstaller.org) is used to install a
toolchain so only MRI is supported at the moment.

## Documentation

- See [repository rules](docs/repository_rules.md) for the documentation of `WORKSPACE` rules.
- See [rules](docs/rules.md) for the documentation of `BUILD` rules.
