---
title: setup-ols.sh
summary: A script that installs OpenLiteSpeed and configures it for usage
tags:
- Linux Administration
- Bash
- Packages
date: "2020-02-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/setup-scripts/setup-ols.sh
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
This script first uses [litespeedtech/ols1clk](https://github.com/litespeedtech/ols1clk) to install OpenLiteSpeed.

It also updates the port mapping and updates the admin password, printing it to the console.

Usage:
```sh
wget https://jrussell.io/setup-ols && sudo bash setup-ols
```