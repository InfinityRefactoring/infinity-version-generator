[![Infinity Refactoring](https://goo.gl/8YUdB6)](https://infinityrefactoring.com)

# Infinity Version Generator

[![GitHub issues](https://img.shields.io/github/issues/InfinityRefactoring/infinity-version-generator.svg)](https://github.com/InfinityRefactoring/infinity-version-generator)
[![GitHub stars](https://img.shields.io/github/stars/InfinityRefactoring/infinity-version-generator.svg)](https://github.com/InfinityRefactoring/infinity-version-generator)

## What is it?

A flexible version generator for projects that uses the Git as control version.
The generated version is based in the git commit time and the git commit hash and an optional suffix.

## Using Infinity Version Generator

1. [Download](https://github.com/InfinityRefactoring/infinity-version-generator/archive/master.zip) the source code
1. Extract to the `~/InfinityRefactoring/infinity-version-generator` folder
1. `chmod +x ~/InfinityRefactoring/infinity-version-generator/bash/ivg`
1. Add the line `PATH="$HOME/InfinityRefactoring/infinity-version-generator/bash:$PATH"` to the end of `~/.profile` file
1. Restart the system to reload the `~/.profile` file or use the `source ~/.profile` command
1. Run `ivg --help` to test

## Tested on

Linux Mint 19 Cinnamon

## Licensing

**InfinityRefactoring/infinity-version-generator** is provided and distributed under the [Apache Software License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

Refer to *LICENSE* for more information.
