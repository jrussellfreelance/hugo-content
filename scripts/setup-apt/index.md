---
title: setup-apt.sh
summary: A script that configures apt after initial login
tags:
- Linux Administration
- Bash
- Packages
date: "2020-01-20T00:00:00Z"

image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/setup-scripts/setup-apt.sh
---
This script updates the apt cache, performs upgrades, and removes unneeded packages.

Usage:
```sh
bash <(curl -sSL https://jrussell.io/setup-apt)
```
Full Script:
```sh
#!/bin/bash
# Designed for Ubuntu
# Update the apt cache
apt update
# Perform updates
apt -y upgrade
apt -y dist-upgrade
# Remove uneeded packages
apt -y autoremove
```