---
title: Radio Firmware
publishDate: 2023-08-01 00:00:00
img: /assets/images/hornet.webp
img_alt: Rugged radio endpoint for use in mining vehicles
description: |
  The software system for rugged mining radio endpoints.
tags:
  - Development
  - Networking
---

## Description

My client produces heavy duty networking radio equipment for mining operations.  The 'firmware' that runs these radios is a custom Linux solution utilizing 3rd party components and in-house software. The firmware requires consistent releases and adaptation to hardware changes for newer hardware models.  This all gets compiled into a installer that can run from within the existing system, or from a physical USB stick.  In this way fleets can be updated as needed without forcing the mining vehicles back to the shop for maintenance. 

## Role

My role in this ecosystem was to ensure the firmware build system was stable and reliable.  I worked with the very skilled engineers and system-level developers to bring the software together into a deliverable package.  Kernel customization and other low-level tweaks were often needed.  I automated the whole process to build the custom Linux installer in under 15 minutes. I also created tools to track the state of various elements to determine if they were ready for the next release.  Thorough testing was done of the generated installer across a sampling of all supported radio models.  My code was used to track the state of this testing on the models.  These tools and automations allowed a quarterly release cycle for the Firmware system.",
