# BackPack-Installer

Simple installer for [BackPack](https://github.com/WhatDaFox/BackPack).

Inspired by [Laravel Installer](https://github.com/laravel/installer)

## Usage

To generate boilerplate for your new PHP package, just execute the command:

```
backpack new PackageName --namespace="Package"
```

The `namespace` option defaults to `BackPack`.


## Installation

Install this package as a global dependency:

```
composer global require "whatdafox/backpack-installer=~1.0"
```

You may want to add `~/.composer/vendor/bin` 

## Contribute

Feel free to contribute to this project, the goal is to have a tool to quickly generate PHP packages.

The next would be to create framework related providers with an option, ex.: a `PackageServiceProvider` for Laravel Framework.