---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi Camera DeeptTAM"
summary: "3D Vision Project to extend DeepTAM for Multi Camera"
authors: []
tags: [vision]
categories: []
date: 2019-12-04T09:20:18+01:00

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/surirohit/multi-camera-deeptam"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

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
Visual Odometry methods based on classical 3D geometry have been around for years, using either indirect feature matching or direct visual error minimization. Lately,learning-based methods that combine both matching and geometry estimation in a single network have achieved impressive results. One such method is DeepTAM. Further, it has been shown that classical methods benefit from the extended field of view provided by using multiple cameras. However, these setups have been ignored by current learning-based methods.

In this work, we extend the existing DeepTAM pipeline to leverage a multi-camera setup with known geometry. We demonstrate the generalizability of DeepTAM to other monocular setups and highlight the scenarios in which it performs poorly. We show the efficacy of our proposed multi-camera VO pipeline to receive better pose estimates using experiments based on simulation.

Contributors: Mayank Mittal, Rohit Suri, Fadhil Ginting, Parker Ewen

https://github.com/surirohit/multi-camera-deeptam
