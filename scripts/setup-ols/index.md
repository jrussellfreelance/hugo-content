---
title: setup-ols.sh
summary: A script that installs OpenLiteSpeed and configures it for usage
tags:
- Linux Administration
- Bash
- Packages
date: "2020-02-27T00:00:00Z"
image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/setup-scripts/setup-ols.sh
---
This script first uses [litespeedtech/ols1clk](https://github.com/litespeedtech/ols1clk) to install OpenLiteSpeed.

It also updates the port mapping and updates the admin password, printing it to the console.

Usage:
```sh
bash <(curl -sSL https://jrussell.io/setup-ols)
```