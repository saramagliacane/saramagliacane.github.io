---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Graph Switching Dynamical Systemss in Interactive Systems
subtitle: ''
summary: ''
authors:
- Yongtuo Liu
- admin
- Miltos Kofinas
- Efstratios Gavves
tags: 
  - dynamical systesm
categories: []
date: '2023-03-01'
lastmod: 2023-03-25T14:52:04+02:00
featured: false
draft: false

url_pdf: 'https://openreview.net/forum?id=rW6ENT7EtX'
url_code: 'https://github.com/yongtuoliu/Graph-Switching-Dynamical-Systems'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: 'https://icml.cc/media/PosterPDFs/ICML%202023/24872.png?t=1689664913.4659803'
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
publishDate: '2022-10-27T12:52:04.227349Z'
publication_types:
- '1'
abstract: 
  Dynamical systems with complex behaviours, e.g. immune system cells interacting with a pathogen, are commonly modelled by splitting the behaviour in different regimes, or modes, each with simpler dynamics, and then learn the switching behaviour from one mode to another. To achieve this, Switching Dynamical Systems (SDS) are a powerful tool that automatically discovers these modes and mode-switching behaviour from time series data. While effective, these methods focus on independent objects, where the modes of one object are independent of the modes of the other objects. In this paper, we focus on the more general interacting object setting for switching dynamical systems, where the per-object dynamics also depend on an unknown and dynamically changing subset of other objects and their modes. To this end, we propose a novel graph-based approach for switching dynamical systems, GRAph Switching dynamical Systems (GRASS), in which we use a dynamic graph to characterize interactions between objects and learn both intra-object and inter-object mode-switching behaviour. For benchmarking, we create two new datasets, a synthesized ODE-driven particles dataset and a real-world Salsa-couple dancing dataset. Experiments show that GRASS can consistently outperforms previous state-of-the-art methods. We will release code and data after acceptance.
publication: '*Proceedings of the International Conference on Machine Learning 2023*'
links:
- name: URL
  url: https://openreview.net/forum?id=rW6ENT7EtX
---
