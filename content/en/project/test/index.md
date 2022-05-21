---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Test"
summary: ""
authors: [Dongheng Zhang]
tags: [object track ]
categories: []
date: 2021-08-07T19:45:56+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "framework"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Follow
  url: https://twitter.com
  icon_pack: fab
  icon: twitter

social:
- icon: envelope
  icon_pack: fas
  link: 'mailto:ChunyangXie@std.uestc.edu.cn'

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

We propose a human sensing system with radio signals, MTrack, for in-home healthcare, which is capable of tracking the trajectories of moving persons and vital signs of static persons under the multi-person scenarios. To achieve this, we implement a multi-antenna wideband system that can provide high-resolution angle of arrival (AoA) and time of flight (ToF). A 2D beamformer is utilized to transform the raw radio signals into the AoA-ToF domain. To track the trajectories of moving persons, we leverage the movement of persons to cancel static multipaths and propose a path selection algorithm to estimate the locations of human and suppress the interferences from dynamic multipaths. To track the vital signs of static persons, we utilize the breath of static persons to eliminate static multipaths and propose a correlation-based algorithm to eliminate dynamic multipaths. Extensive experiments show that the proposed MTrack system is capable of tracking multiple moving persons with sub-decimeter level accuracy, and can estimate the breath and heartbeat rate of static persons with median accuracy of 99.8% and 98.46%, respectively.