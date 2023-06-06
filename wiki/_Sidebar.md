# User guide

## [System requirements](system-requirements.md)

## [UnitTestBot server](install-server.md)

* [**Linux**](linux.md)
   * [Local installation](install-server-on-ubuntu.md)
   * [Remote installation via Docker](linux-remote.md)
* [**Windows**](windows.md)
   * [Local installation via WSL](windows-local.md)
   * [Remote installation via Docker](windows-remote.md)
* [**macOS**](macos.md)

## [UnitTestBot client](install_client.md)

### [Visual Studio Code plugin](vscode-overall.md)

* [Install and configure the plugin](vscode-install-and-configure.md)
* [Generate tests with default configuration](vscode-generate-tests.md)
* [Fine-tune test generation](vscode-fine-tune.md)
* [Get use of test results](vscode-get-use-of-results.md)

### [CLion plugin](clion-overall.md)

* [Install and configure the plugin](clion-install-and-configure.md)
* [Generate tests with default configuration](clion-generate-tests.md)
* [Fine-tune test generation](clion-fine-tune.md)
* [Get use of test results](clion-get-use-of-results.md)

## [GitHub Action](github-action.md)

## Supported syntax

* [C](c-syntax.md)
* [C++](cpp-syntax.md)

# Contributor guides

## Developer guides

* [To do](todo)
* [Create a release](create-release)
* [Testing release in Docker](testing-release-utbotcpp-in-docker)
* [Label usage guideline](Labels-usage-guidelines)
* [Troubleshooting](troubleshooting.md)

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
