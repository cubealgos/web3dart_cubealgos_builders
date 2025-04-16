> This packages was forked from [inveker/web3dart_builders](https://github.com/inveker/web3dart_builders), below is the original README -> the project still follows it's API, the only thing changed is that this uses web3dart_cubealgos internally

# Description

Helper package for the ([cubealgos/web3dart_cubealgos](https://github.com/cubealgos/web3dart_cubealgos)) library responsible for generating dart classes from abi contracts
This project is part of this repository [cubealgos/web3dart_cubealgos](https://github.com/cubealgos/web3dart_cubealgos).

# Requirements

web3dart 2.5.1

# Installation

1. Add to pubspec.yaml in your project: dev_dependencies: web3dart_cubealgos_builders: ^0.1.2 or call

```shell
dart pub add build_runner --dev
```

```shell
dart pub add web3dart_cubealgos_builders --dev
```

# Usage

```shell
dart pub run build_runner build
```

or

```shell
dart pub run build_runner watch
```

# Test

```shell
dart test
```
