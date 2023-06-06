# User guide

## [System requirements](system-requirements)

## [UnitTestBot server](install-server)

* [**Linux**](linux)
   * [Local installation](install-server-on-ubuntu)
   * [Remote installation via Docker](linux-remote)
* [**Windows**](windows)
   * [Local installation via WSL](windows-local)
   * [Remote installation via Docker](windows-remote)
* [**macOS**](macos)

## [UnitTestBot client](install_client)

### [Visual Studio Code plugin](vscode/vscode-overall.md)

* [Install and configure the plugin](vscode/vscode-install-and-configure.md)
* [Generate tests with default configuration](vscode/vscode-generate-tests.md)
* [Fine-tune test generation](vscode/vscode-fine-tune.md)
* [Get use of test results](vscode/vscode-get-use-of-results.md)

### [CLion plugin](clion/clion-overall.md)

* [Install and configure the plugin](clion/clion-install-and-configure.md)
* [Generate tests with default configuration](clion/clion-generate-tests.md)
* [Fine-tune test generation](clion/clion-fine-tune.md)
* [Get use of test results](clion/clion-get-use-of-results.md)

## [GitHub Action](GitHub-action)

## Supported syntax

* [C](c-syntax)
* [C++](cpp-syntax)

# Contributor guides

## Developer guides

* [To do](todo)
* [Create a release](create-release)
* [Testing release in Docker](testing-release-utbotcpp-in-docker)
* [Label usage guideline](Labels-usage-guidelines)
* [Troubleshooting](troubleshooting)

## Advanced

* [How UTBot Works](utbot-inside)
* [How types are fetched and stored](types-fetching)
* [Makefiles](makefiles)
* [Symbolic Stdin](symbolic-stdin)
* [UTBot Logging Principles](utbot-logging)
* [Targets](targets)
* [Compile database](compile-database)
* [Coverage](coverage)
* [Generating and running test](generating-and-running-tests)
* [Incrementality](incrementality)
* [Linking bitcode](linking-bitcode)
* [Preparing source for klee](preparing-sources-for-klee)
* [Stubs inside](stubs-inside)
* [KLEE patches](klee-patches)
* [Lazy initialization](LI)
* [Symcretes](Symcretes)
* [Objects of symbolic size](Symsizes)
