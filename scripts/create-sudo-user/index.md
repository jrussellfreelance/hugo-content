---
title: create-sudo-user.sh
summary: A command line script to create a sudo user
tags:
- Linux Administration
- Bash
- User Management
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
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/setup-scripts/create-sudo-user.sh
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
This script condenses the few lines of bash needed for creating a new sudo user into a single command.

It prompts the current user for the new user's information.

Usage:
```sh
wget https://jrussell.io/create-sudo-user && sudo bash create-sudo-user
```