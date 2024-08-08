---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Generating Human-Like Goals by Synthesizing Reward-Producing Programs
subtitle: ''
summary: ''
authors:
- Guy Davidson
- Graham Todd
- Todd M. Gureckis
- Julian Togelius
- Brenden M. Lake
tags: []
categories: []
date: '2023-12-01'
lastmod: 2023-11-10T15:02:15-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-08-08T16:46:54.671318Z'
publication_types:
- '1'
abstract: Humans show a remarkable capacity to generate novel goals, for learning
  and play alike, and modeling this human capacity would be a valuable step toward
  more generally-capable artificial agents.  We describe a computational model for
  generating novel human-like goals represented in a domain-specific language (DSL).  We
  learn a ‘human-likeness’ fitness function over expressions in this DSL from a small
  (<100 game) human dataset collected in an online experiment.  We then use a Quality-Diversity
  (QD) approach to generate a variety of human-like games with different characteristics
  and high fitness.  We demonstrate that our method can generate synthetic games that
  are syntactically coherent under the DSL, semantically sensible with respect to
  environmental objects and their affordances, but distinct from human games in the
  training set.  We discuss key components of our model and its current shortcomings,
  in the hope that this work helps inspire progress toward self-directed agents with
  human-like goals.
publication: '*Intrinsically Motivated Open-Ended Learning @ NeurIPS 2023*'
url_pdf: https://guydavidson.me/files/IMOL_Workshop_Modeling_Game_Generation.pdf
---
