---
title: recursive-git-clone.sh
summary: A script that recursively clones git repositories
tags:
- Bash
- Git
date: "2020-03-03T00:00:00Z"
image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/git-scripts/recursive-git-clone.sh
---
This script recursively prompts you for a git URL, cloning the repo into the current directory.

Usage:
```sh
bash <(curl -sSL https://jrussell.io/recursive-git-clone)
```
Full Script:
```sh
#!/bin/bash
# Tested on Ubuntu 18.04 LTS
# This script endlessly prompts for a git URL and clones it into the current directory
while [ 1 ] ; do
read -p "ENTER GIT URL >> " NAME
git clone $NAME
done
```