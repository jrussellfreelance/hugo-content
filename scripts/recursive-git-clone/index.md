---
title: recursive-git-clone.sh
summary: A script that recursively clones git repositories
tags:
- Bash
- Git
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
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/git-scripts/recursive-git-clone.sh
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
This script recursively prompts you for a git URL, cloning the repo into the current directory.

Usage:
```sh
wget https://jrussell.xyz/recursive-git-clone && bash recursive-git-clone
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