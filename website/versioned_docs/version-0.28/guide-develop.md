---
id: version-0.28-guide-develop
title: Develop ReNative
sidebar_label: Develop ReNative
original_id: guide-develop
---

<img src="https://renative.org/img/ic_construction.png" width=50 height=50 />

## Developing ReNative Locally

If you need full control over whole ReNative build you can clone and develop it locally

```
1) clone git@github.com:pavjacko/renative.git
2) cd renative
3) yarn bootstrap-clean
4) yarn watch
```

At this point your global `$ rnv` command is linked directly into project above.

It's also best way to contribute back to RNV! :)

```
rnv template apply
=> pick renative-template-hello-world
```

#### Windows development

Requirements: Python 2.7, Visual Studio installed or install `windows-build-tools`(https://www.npmjs.com/package/windows-build-tools). **Please make sure you follow the package's instructions, especially running it in PowerShell as Administrator**

## Documentation

[Documentation for CLI](api-cli.md)

[Documentation for RNV](api-rnv.md)

[Documentation for Config](api-config.md)

[Documentation for Runtime](api-renative.md)