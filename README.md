# Yarn Berry Repo Template

Yarn Berry default configuration

## Features

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
