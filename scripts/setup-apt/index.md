---
title: setup-apt.sh
summary: A script that configures apt after initial login
tags:
- Linux Administration
- Bash
- Packages
date: "2020-01-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/setup-scripts/setup-apt.sh
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
This script updates the apt cache, performs upgrades, and removes unneeded packages.

Usage:
```sh
wget https://jrussell.xyz/setup-apt && sudo bash setup-apt
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