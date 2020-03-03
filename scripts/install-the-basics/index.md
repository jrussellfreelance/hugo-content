---
title: install-the-basics.sh
summary: A script that installs basic tools
tags:
- Linux Administration
- Bash
- Packages
date: "2020-01-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/install-scripts/install-the-basics.sh
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
This script installs a basic set of tools and common dependencies.
 - git
 - nano
 - curl
 - wget
 - unzip
 - net-tools
 - build-essential
 - apt-transport-https
 - software-properties-common

Usage:
```sh
wget https://jrussell.xyz/install-the-basics && sudo bash install-the-basics
```