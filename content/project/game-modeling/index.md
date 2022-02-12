---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Playful Goal Modeling"
summary: "How do people generate playful goals? We take first steps towards computational models of playful goals"
authors: []
tags: []
# - Cognitive Science
# - Domain Specific Language
categories: []
date: 2022-02-11T13:16:32-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "(A) playful goal generation, (B) interactive environment, (C) English games, (D) domain-specific language"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/guydav/game-generation-modeling"
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
How do people come up with open-ended goals? Inspired by ideas of intrinsic motivation (Schmidhuber, 2010) and play as proposing and solving arbitrary problems (Chu & Schulz, 2020), we take first steps toward computational modeling of playful goal generation.
We create an embodied, 3D environment resembling a child's bedroom, and ask study participants to play in the environment and then create a scorable game. 
We model games using a domain-specific language, which represents each game as a computer program. 
These programs act as reward-generating functions, mapping states visited by an agent as they play a game to the score they should receive in the game. 
We then analyze our corpus of program representations to highlight four key aspects of human games that would contribute to constructing effective computational models of game generation: creativity, compositionality, common sense, and context sensitivity.
