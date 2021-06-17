---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Domain-invariant Learning in Vehicle Re-identification"
summary: "Vehicle Re-identification (re-id) aims to retrieve matching vehicles across different cameras. Unlike person re-id ..."
authors: []
tags: []
categories: []
date: 2019-05-01

# Optional external URL for project (replaces project detail page).
external_link: ""

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
url_pdf: "/files/SRS2021-QuangTruong.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Vehicle Re-identification (re-id) aims to retrieve matching
vehicles across different cameras. Unlike person re-
id where a person can be easily recognized by pose
or face, vehicles are hard to be distinguished because
they share similar attributes to each other. In our
research project, we leverage the superior performance
of deep neural networks (DNN) on high-level computer
vision tasks to extract discriminative features of each
vehicle. To further enhance the performance of DNNs,
we develop a robust domain-invariant pipeline for multi-
domain learning