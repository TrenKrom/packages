# Linux packages

A collection of my personal build scripts and files for building Linux packages on various Linux distros (Arch, Alpine, etc.)

## PKGBUILDs

Build scripts for creating Arch Linux packages, included in this repo are PKGBUILDs for:

- [llama.cpp](https://github.com/ggml-org/llama.cpp)
- [ggml](https://github.com/ggml-org/ggml)

For more information, visit https://wiki.archlinux.org/title/PKGBUILD

## APKBUILDs

Build scripts for creating Alpine Linux packages, no such scripts are included in this repo yet.

For more information, visit https://wiki.alpinelinux.org/wiki/APKBUILD_Reference

## Tips

### How to use

Arch Linux (example):

```
git clone https://github.com/TrenKron/packages.git
makepkg --dir packages/ggml --rmdeps --syncdeps  --install
```
