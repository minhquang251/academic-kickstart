---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "2048 Solver"
summary: "A simple program to play 2048 automatically."
authors: []
tags: []
categories: []
date: 2017-12-01

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

url_code: "https://github.com/quang-truong/2048-Solver"
url_pdf: ""
url_slides: ""
url_video: "/files/2048_solver.mp4"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Based on recursive algorithm which is used to maximize game score, I developed a simple program to play 2048 automatically. Additionally, I also designed a score function to take the monotonicity of tiles into account, mimicking the strategy of human. The whole program is written in Python with the help of TkInter for graphics.