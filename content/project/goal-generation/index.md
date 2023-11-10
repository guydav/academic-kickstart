---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Generating Human-Like Goals"
summary: "We propose a quality-diversity method to generate human-like goals specified in a domain-specific language."
authors: []
tags: []
# - Cognitive Science
# - Domain Specific Language
categories: []
date: 2023-11-01

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: "(A) playful goal generation, (B) interactive environment, (C) English games, (D) domain-specific language"
#   focal_point: ""
#   preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/guydav/game-generation-modeling"
url_pdf: "https://guydavidson.me/files/IMOL_Workshop_Modeling_Game_Generation.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Humans show a remarkable capacity to generate novel goals, for learning and play alike, and modeling this human capacity would be a valuable step toward more generally-capable artificial agents. 
We describe a computational model for generating novel human-like goals represented in a domain-specific language (DSL). 
We learn a ‘human-likeness’ fitness function over expressions in this DSL from a small (<100 game) human dataset collected in an online experiment. 
We then use a Quality-Diversity (QD) approach to generate a variety of human-like games with different characteristics and high fitness. 
We demonstrate that our method can generate synthetic games that are syntactically coherent under the DSL, semantically sensible with respect to environmental objects and their affordances, but distinct from human games in the training set. 
We discuss key components of our model and its current shortcomings, in the hope that this work helps inspire progress toward self-directed agents with human-like goals.

Presented at the [Intrinsically Motivated Open-ended Learning
](https://imol-workshop.github.io/) Workshop @ NeurIPS 2023. 