---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Goals as Reward-Producing Programs"
summary: "We propose a framework to represent cognitive as reward-producing programs, and learn a model to generate novel ones."
authors: []
tags: []
# - Cognitive Science
# - Domain Specific Language
categories: []
date: 2024-05-01

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
url_pdf: "https://guydavidson.me/files/goals_as_programs.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
People have a remarkable capacity to generate their own goals, beginning with child’s play and continuing into adulthood. 
Despite considerable empirical and computational work on goals and goal-oriented behavior, models are still far from capturing the richness of everyday human goals. 
Here we bridge this gap by collecting a dataset of human-generated playful goals, modeling them as reward-producing programs, and generating novel human-like goals through program synthesis. 
Reward-producing programs capture the rich semantics of goals through symbolic operations that compose and add temporal constraints, and allow for program execution on behavioral traces to evaluate progress. 
To build a generative model of goals, we learned a fitness function over the infinite set of possible goal programs, and sample novel goals with a quality-diversity algorithm. 
Human evaluators found the model’s better samples indistinguishable from human-created games.
We also discovered that our model’s internal fitness scores predict games that are evaluated as more fun to play and more human-like.

Presented at the [Intrinsically Motivated Open-ended Learning
](https://imol-workshop.github.io/) Workshop @ NeurIPS 2023, journal-length version soon to be submitted.
