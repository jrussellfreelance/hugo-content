---
title: setup-samba.sh
summary: A script that sets up an external drive as a samba share
tags:
- Linux Administration
- Bash
- Raspberry Pi
date: "2020-01-20T00:00:00Z"

external_link: ""

image:
  caption: Screenshot
  focal_point: Smart
links:
- icon: code
  icon_pack: fas
  name: Download Script
  url: https://raw.githubusercontent.com/JacFearsome/bash-scripts/master/raspberrypi-scripts/setup-samba.sh
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
slides: ""
---
`setup-samba.sh` guides you through the process of creating a samba user and mounting an external drive as a SMB share.
This script was designed for a Raspberry Pi running Ubuntu 18.04 with an external drive attached.  It was tested on a 2b and a 4.

Usage:
```sh
wget https://jrussell.io/setup-samba && sudo bash setup-samba
```