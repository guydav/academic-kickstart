---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Infant Relation Categorization"
summary: "We use several types of deep neural networks to model various results in infant relation categorization"
authors: []
tags: []
categories: []
date: 2021-07-27

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "The familiarization stimulus (center) has the same category (below) as the example on the left"
  focal_point: "Top"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/guydav/simple-relational-reasoning/tree/quinn"
url_pdf: "https://escholarship.org/uc/item/8sm6b1b4"
url_slides: "https://drive.google.com/file/d/1Zzh6e3J7KN1-bySxGfbEMBx1bY4_ymq2/view?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Categorizing spatial relations is central to the development of visual understanding and spatial cognition, with roots in the first few months of life.
Quinn (2003) reviews two findings in infant relation categorization: categorizing one object as above/below another precedes categorizing an object as between other objects, and categorizing relations over specific objects predates abstract relations over varying objects.
We model these phenomena with deep neural networks, including contemporary architectures specialized for relational learning and vision models pretrained on baby headcam footage \citep{Sullivan2020}.
Across two computational experiments, we can account for most of the developmental findings, suggesting these neural network models are useful for studying the computational mechanisms of infant categorization.  