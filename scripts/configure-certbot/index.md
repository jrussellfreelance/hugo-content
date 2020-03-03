---
title: configure-certbot.sh
summary: A command line utility for installing and running certbot
tags:
- Linux Administration
- Bash
- SSL
- HTTPS
date: "2020-01-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/web-server-scripts/configure-certbot.sh
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
This script allows you to install and configure certbot as well as the Nginx and Cloudflare addons.

Usage:
```sh
wget https://jrussell.xyz/configure-certbot && sudo bash configure-certbot
```
