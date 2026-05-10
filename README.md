# microVM LATX Workspace

This repository coordinates the four component repositories used to run x86
applications through LATX inside a 4K-page microVM kernel on LoongArch hosts
that commonly use 16K kernel pages.

Submodules:

- `libkrun`: microVM VMM library.
- `libkrunfw`: firmware used by libkrun.
- `muvm`: user-facing microVM launcher/runtime integration.
- `lat`: LATX/QEMU-derived x86 binary translator tree.

Basic status check:

```sh
git status
git submodule status
```
