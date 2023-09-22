---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Causal Representation Learning for Instantaneous and Temporal Effects in Interactive Systems
subtitle: ''
summary: ''
authors:
- Phillip Lippe
- admin
- Sindy Löwe
- Yuki M Asano
- Taco Cohen
- Efstratios Gavves
tags: 
  - causal representation learning
  - CITRIS
categories: []
date: '2023-03-01'
lastmod: 2023-03-25T14:52:04+02:00
featured: false
draft: false

url_pdf: 'https://proceedings.mlr.press/v216/lippe23a/lippe23a.pdf'
url_code: 'https://github.com/phlippe/BISCUIT'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: 'https://phlippe.github.io/media/iCITRIS_Poster_A0.pdf'
url_project: 'https://phlippe.github.io/BISCUIT/'
url_slides: 'https://phlippe.github.io/media/BISCUIT_Slides.pdf'
#url_source: 'https://proceedings.neurips.cc/paper/2018/file/39e98420b5e98bfbdc8a619bef7b8f61-Paper.pdf'





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
#projects: CITRIS
publishDate: '2022-10-27T12:52:04.227349Z'
publication_types:
- '1'
abstract: 
  Identifying the causal variables of an environment and how to intervene on them is of core value in applications such as robotics and embodied AI. While an agent can commonly interact with the environment and may implicitly perturb the behavior of some of these causal variables, often the targets it affects remain unknown. In this paper, we show that causal variables can still be identified for many common setups, e.g., additive Gaussian noise models, if the agent’s interactions with a causal variable can be described by an unknown binary variable. This happens when each causal variable has two different mechanisms, e.g., an observational and an interventional one. Using this identifiability result, we propose BISCUIT, a method for simultaneously learning causal variables and their corresponding binary interaction variables. On three robotic-inspired datasets, BISCUIT accurately identifies causal variables and can even be scaled to complex, realistic environments for embodied AI.
publication: '*Proceedings of the Thirty-Ninth Conference on Uncertainty in Artificial Intelligence*'
links:
- name: URL
  url: https://phlippe.github.io/BISCUIT/
---
