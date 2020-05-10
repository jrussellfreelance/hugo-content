---
title: create-sudo-user.sh
summary: A command line script to create a sudo user
tags:
- Linux Administration
- Bash
- User Management
date: "2020-01-20T00:00:00Z"

image:
  caption: Screenshot
  focal_point: Smart

links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/setup-scripts/create-sudo-user.sh
---
This script condenses the few lines of bash needed for creating a new sudo user into a single command.

It prompts the current user for the new user's information.

Usage:
```sh
bash <(curl -sSL https://jrussell.io/create-sudo-user)
```