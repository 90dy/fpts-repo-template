# Welcome to yarn-repo-template 👋
[![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen.svg)](https://github.com/gponsinet/git-repo-template/blob/master/README.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#)
[![Twitter: _godfpsn](https://img.shields.io/twitter/follow/_godfpsn.svg?style=social)](https://twitter.com/_godfpsn)

> Yarn Repository Template

### 🏠 [Homepage](https://github.com/gponsinet/yarn-repo-template)

## Install

```sh
make all
```

## Features

```sh
yarn
```
### Version

Apply a new version to the current package.

```
yarn version [-d,--deferred] [-i,--immediate] [-f,--force] <strategy>
```

### Upgrade Interactive

This command opens a fullscreen terminal interace where you can see the packages used by your application, their status compared to the latest versions available on the remote registry, and let you upgrade.

```
yarn upgrade-interactive
```

### Stage

This command will add to your staging area the files belonging to Yarn.

```
yarn stage [-c,--commit] [-r,--reset] [-u,--update] [-n,--dry-run]
```

### Typescript

Automatically adds @types/ packages into your dependencies when you add a package that doesn't include its own types.

### Workspace

Adds support for various workspace-related commands.

```
yarn workspace <workspaceName> <commandName> ...
```

## Author

👤 **Godefroy Ponsinet **

* Website: https://github.com/gponsinet
* Twitter: [@_godfpsn](https://twitter.com/_godfpsn)
* Github: [@gponsinet](https://github.com/gponsinet)

## Show your support

Give a ⭐️ if this project helped you!

[![support us](https://img.shields.io/badge/become-a patreon%20us-orange.svg?cacheSeconds=2592000)](https://www.patreon.com/gponsinet)


***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
