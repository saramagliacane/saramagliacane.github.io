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

url_pdf: 'https://openreview.net/pdf?id=itZ6ggvMnzS'
url_code: 'https://github.com/phlippe/CITRIS'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: 'https://phlippe.github.io/media/iCITRIS_Poster_A0.pdf'
#url_project: ''
#url_slides: 'https://phlippe.github.io/media/UAI2022_CRL_Invited_Talk.pdf'
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
  Causal representation learning is the task of identifying the underlying causal variables and their relations from high-dimensional observations, such as images. Recent work has shown that one can reconstruct the causal variables from temporal sequences of observations under the assumption that there are no instantaneous causal relations between them. In practical applications, however, our measurement or frame rate might be slower than many of the causal effects. This effectively creates ``instantaneous' effects and invalidates previous identifiability results. To address this issue, we propose iCITRIS, a causal representation learning method that allows for instantaneous effects in intervened temporal sequences when intervention targets can be observed, e.g., as actions of an agent. iCITRIS identifies the potentially multidimensional causal variables from temporal observations, while simultaneously using a differentiable causal discovery method to learn their causal graph. In experiments on three datasets of interactive systems, iCITRIS accurately identifies the causal variables and their causal graph.
publication: '*ICLR 2023*'
links:
- name: URL
  url: https://openreview.net/forum?id=itZ6ggvMnzS
---
