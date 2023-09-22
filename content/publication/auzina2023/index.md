---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Modulated Neural ODEs
subtitle: ''
summary: ''
authors:
- Ilze Amanda Auzina
- Cagatay Yildiz
- admin
- Matthias Bethge
- Efstratios Gavves
tags: 
  - dynamical systems
categories: []
date: '2023-03-01'
lastmod: 2023-09-21T14:52:04+02:00
featured: false
draft: false

url_pdf: 'https://arxiv.org/pdf/2302.13262.pdf'
#url_code: 'https://github.com/yongtuoliu/Graph-Switching-Dynamical-Systems'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: 'https://icml.cc/media/PosterPDFs/ICML%202023/24872.png?t=1689664913.4659803'
#url_project: 'https://phlippe.github.io/BISCUIT/'
#url_slides: 'https://phlippe.github.io/media/BISCUIT_Slides.pdf'
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
publishDate: '2023-9-22T15:52:04.227349Z'
publication_types:
- '1'
abstract: 
  'Neural ordinary differential equations (NODEs) have been proven useful for learning non-linear dynamics of arbitrary trajectories. However, current NODE methods
capture variations across trajectories only via the initial state value or by autoregressive encoder updates. In this work, we introduce Modulated Neural ODEs
(MoNODEs), a novel framework that sets apart dynamics states from underlying
static factors of variation and improves the existing NODE methods. In particular,
we introduce time-invariant modulator variables that are learned from the data.
We incorporate our proposed framework into four existing NODE variants. We test
MoNODE on oscillating systems, videos and human walking trajectories, where
each trajectory has trajectory-specific modulation. Our framework consistently
improves the existing model ability to generalize to new dynamic parameterizations
and to perform far-horizon forecasting. In addition, we verify that the proposed
modulator variables are informative of the true unknown factors of variation as
measured by R2
scores.'
publication: '*NeurIPS 2023*'
links:
- name: URL
  url: https://arxiv.org/pdf/2302.13262.pdf
---
