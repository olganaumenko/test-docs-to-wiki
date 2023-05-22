# User guide

## 0 – [Intro](https://github.com/UnitTestBot/UTBotCpp/wiki/Intro)

* [What is UnitTestBot C/C++](https://github.com/UnitTestBot/UTBotCpp/wiki/Intro#what-is-unittestbot-cc)
* [Why to install both server and client](https://github.com/UnitTestBot/UTBotCpp/wiki/Intro#why-to-install-both-server-and-client)
* [Make sure you can build your project](https://github.com/UnitTestBot/UTBotCpp/wiki/Intro#make-sure-you-can-build-your-project)
* [Check the supported language features](https://github.com/UnitTestBot/UTBotCpp/wiki/Intro#check-the-supported-language-features)

## 1 – [Check system requirements](https://github.com/UnitTestBot/UTBotCpp/wiki/system-requirements)

## 2 – [Install the UnitTestBot server](https://github.com/UnitTestBot/UTBotCpp/wiki/install-server)

* [For **Linux** or **macOS**](https://github.com/UnitTestBot/UTBotCpp/wiki/linux-macos)
   * [Set up Docker](https://github.com/UnitTestBot/UTBotCpp/wiki/set-up-docker-os)
   * [Install dependencies and GCC](https://github.com/UnitTestBot/UTBotCpp/wiki/install-dependencies-gcc9)
   * [Install server](https://github.com/UnitTestBot/UTBotCpp/wiki/install-server-on-ubuntu)
* [For **Windows**](https://github.com/UnitTestBot/UTBotCpp/wiki/windows)
   * Using WSL
      * [Set up WSL](https://github.com/UnitTestBot/UTBotCpp/wiki/install-wsl)
      * [Install dependencies and GCC](https://github.com/UnitTestBot/UTBotCpp/wiki/install-dependencies-gcc9)
      * [Install server](https://github.com/UnitTestBot/UTBotCpp/wiki/install-server-on-ubuntu)
   * Using Docker via WSL
      * [Set up WSL](https://github.com/UnitTestBot/UTBotCpp/wiki/install-wsl)
      * [Set up Docker](https://github.com/UnitTestBot/UTBotCpp/wiki/set-up-docker-os)
      * [Install dependencies and GCC](https://github.com/UnitTestBot/UTBotCpp/wiki/install-dependencies-gcc9)
      * [Install server](https://github.com/UnitTestBot/UTBotCpp/wiki/install-server-on-ubuntu)

## 3 – [Install the UnitTestBot client](https://github.com/UnitTestBot/UTBotCpp/wiki/install_client)

### 3a – [Visual Studio Code plugin](https://github.com/UnitTestBot/UTBotCpp/wiki/vscode-overall)

* [Install and configure the plugin](https://github.com/UnitTestBot/UTBotCpp/wiki/vscode-install-and-configure)
* [Generate tests with default configuration](https://github.com/UnitTestBot/UTBotCpp/wiki/vscode-generate-tests)
* [Fine-tune test generation](https://github.com/UnitTestBot/UTBotCpp/wiki/vscode-fine-tune)
* [Get use of test results](https://github.com/UnitTestBot/UTBotCpp/wiki/vscode-get-use-of-results)

### 3b – [CLion plugin](https://github.com/UnitTestBot/UTBotCpp/wiki/clion-overall)

* [Install and configure the plugin](https://github.com/UnitTestBot/UTBotCpp/wiki/clion-install-and-configure)
* [Generate tests with default configuration](https://github.com/UnitTestBot/UTBotCpp/wiki/clion-generate-tests)
* [Fine-tune test generation](https://github.com/UnitTestBot/UTBotCpp/wiki/clion-fine-tune)
* [Get use of test results](https://github.com/UnitTestBot/UTBotCpp/wiki/clion-get-use-of-results)

### 4 – [Run GitHub Action](https://github.com/UnitTestBot/UTBotCpp/wiki/GitHub-action)

## Supported syntax

* [C](https://github.com/UnitTestBot/UTBotCpp/wiki/c-syntax)
* [C++](https://github.com/UnitTestBot/UTBotCpp/wiki/cpp-syntax)

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
