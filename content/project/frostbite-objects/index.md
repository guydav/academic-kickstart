---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Simple Object Representations"
summary: "We add simple object representations to a deep RL algorithm and study the results"
authors: []
tags: []
categories: []
date: 2020-07-27

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Example object masks for each object category in Atari Frostbite"
  focal_point: "top"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/guydav/Rainbow/tree/augmentation"
url_pdf: "https://cogsci.mindmodeling.org/2020/papers/0466/0466.pdf"
url_slides: "https://drive.google.com/file/d/1_SM9dqbWorY8gf31jq8Skn4RTpVjjxc1/view?usp=sharing"
url_video: "https://drive.google.com/file/d/1hpuM_mBuPE9YMsbO7quSE9ciVvXitly8/view?usp=sharing"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
We explore the benefits of augmenting state-of-the-art model-free deep reinforcement learning with simple object representations.
Following the Frostbite challenge posited by Lake et al. (2017), we identify object representations as a critical cognitive capacity lacking from current reinforcement learning agents.
We discover that providing the Rainbow model (Hessel et al., 2018) with simple, feature-engineered object representations substantially boosts its performance on the Frostbite game from Atari 2600.
We then analyze the relative contributions of the representations of different types of objects, identify environment states where these representations are most impactful, and examine how these representations aid in generalizing to novel situations.

Published at CogSci 2020.