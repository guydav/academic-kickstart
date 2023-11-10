---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Infant Relation Categorization"
summary: "We use several types of deep neural networks to model various results in infant relation categorization"
authors: []
tags: []
categories: []
date: 2023-10-20

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Left: infant relation categorization is studied in the lab using a novelty-preference paradigm. Right: we model this paradigm using deep neural networks. "
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
url_pdf: "https://osf.io/preprints/psyarxiv/ykejp"
url_slides: "https://drive.google.com/file/d/1Zzh6e3J7KN1-bySxGfbEMBx1bY4_ymq2/view?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Spatial relations, such as above, below, between, and containment, are important mediators in children’s understanding of the world (Piaget, 1954). 
The development of these relational categories in infancy has been extensively studied (Quinn, 2003) yet little is known about their computational underpinnings. 
Using developmental tests, we examine the extent to which deep neural networks, pretrained on a standard vision benchmark or egocentric video captured from one baby’s perspective, form categorical representations for visual stimuli depicting relations. 
Notably, the networks did not receive any explicit training on relations. 
We then analyze whether these networks recover similar patterns to ones identified in the development, such as reproducing the relative difficulty of categorizing different spatial relations and different stimulus abstractions. 
We find that the networks we evaluate tend to recover many of the patterns observed with the simpler relations of “above versus below” or “between versus outside”, but struggle to match developmental findings related to “containment”. 
We identify factors in the choice of model architecture, pretraining data, and experimental design that contribute to the extent the networks match developmental patterns, and highlight experimental predictions made by our modeling results. 
Our results open the door to modeling infants’ earliest categorization abilities with modern machine learning tools and demonstrate the utility and productivity of this approach.

Initially published at [CogSci 2021](https://escholarship.org/uc/item/8sm6b1b4), a [longer version](https://osf.io/preprints/psyarxiv/ykejp) is currently under review.