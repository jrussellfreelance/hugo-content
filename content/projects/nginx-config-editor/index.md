---
title: Nginx Config Editor
summary: A web-based tool for remotely editing Nginx configs
tags:
- Nginx
- Linux Administration
- Node.js
date: "2019-09-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Screenshot
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: View on GitHub
  url: https://github.com/JacFearsome/nginx-config-editor
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

<div class="github-card" data-github="jacfearsome/nginx-config-editor" data-width="725" data-height="155" data-theme="default"></div>
<script src="//cdn.jsdelivr.net/github-cards/latest/widget.js"></script>

This is a simple web-based tool to edit nginx configuration files.  With it you can remotely edit configuration files, create new configuration files, check the files for syntax errors, as well as restart the nginx service.

This project is mostly for convenience, obviously you can edit nginx configuration files from SSH just fine.  This app has common tools readily accessible as a button, instead of having to exit out of nano or vim to restart the nginx service.