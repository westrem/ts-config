# `@westrem/ts-config`

Base config for TypeScript

# How to use

**Install**

```
yarn add --dev @westrem/ts-config
```

**Usage**

```
// tsconfig.json
{
  "extends": "@westrem/ts-config",
}
```

**Notable info from docs**

The configuration from the base file are loaded first, then overridden by those in the inheriting config file. All relative paths found in the configuration file will be resolved relative to the configuration file they originated in.

It’s worth noting that files, include and exclude from the inheriting config file overwrite those from the base config file, and that circularity between configuration files is not allowed.


[Extends field documentation](https://www.typescriptlang.org/tsconfig#extends)