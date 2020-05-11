---
title: install-homebrew.sh
summary: A script to install homebrew
tags:
- Linux Administration
- Bash
- Packages
date: "2020-01-23T00:00:00Z"
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/install-scripts/install-homebrew.sh
---
This script downloads homebrew and adds it to your PATH.

It also installs `gcc` through brew as well as the `patchelf` apt package.

Usage:
```sh
curl -sSL https://jrussell.io/install-homebrew | bash
```
