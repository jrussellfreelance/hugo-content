---
title: install-homebrew.sh
summary: A script to install homebrew
tags:
- Linux Administration
- Bash
- Packages
date: "2020-01-23T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot
  focal_point: Smart

links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/install-scripts/install-homebrew.sh
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
This script downloads homebrew and adds it to your PATH.

It also installs `gcc` through brew as well as the `patchelf` apt package.

Usage:
```sh
curl -sSL https://jrussell.io/install-homebrew | bash
```
