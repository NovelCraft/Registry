# NovelCraft's Dedicated Lip Registry

This is NovelCraft's dedicated Lip registry. It contains all the packages that are published by NovelCraft.

Before using Lip to install any package, you need to set environment variable `LIP_REGISTRY` to the URL of this registry. For example, on Windows, you can run `set LIP_REGISTRY=https://novelcraft.github.io/Registry` in the command line.

For Lip users, you do not need to do any configuration. Just run `lip install <alias>` and Lip will automatically fetch the package from the official registry. For example, `lip install lip` will install the latest version of Lip.