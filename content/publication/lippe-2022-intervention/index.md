---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Intervention Design for Causal Representation Learning
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
date: '2022-01-01'
lastmod: 2022-10-27T14:52:04+02:00
featured: false
draft: false

url_pdf: 'https://openreview.net/pdf?id=TpVzjh4M2hd'
url_code: 'https://github.com/phlippe/CITRIS'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: 'https://phlippe.github.io/media/Intervention_Design_Poster_A0.pdf'
#url_project: ''
url_slides: 'https://phlippe.github.io/media/UAI2022_CRL_Invited_Talk.pdf'
#url_source: 'https://proceedings.neurips.cc/paper/2018/file/39e98420b5e98bfbdc8a619bef7b8f61-Paper.pdf'
url_video: 'https://www.youtube.com/watch?v=z748Lf4QTlE&feature=youtu.be'




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
  In this paper, we take a first step towards bringing two fields of causality closer together, intervention design and causal representation learning. Intervention design is a well studied task in classic causal discovery, which aims at finding the minimal sets of experiments under which the causal graph can be identified. Causal representation learning aims at recovering causal variables from high-dimensional entangled observations. In recent work in causal representation, interventions are exploited to improve identifiability, similarly to classic causal discovery. Hence, the same task becomes relevant in this setting as well, how many experiments are minimally needed to identify the latent causal variables? Based on the recent causal representation learning method CITRIS, we show that for  causal variables,  experiments are sufficient to identify causal variables from temporal, intervened sequences, which is only one more experiment than needed for classic causal discovery in the worst case. Further, we show that this bound holds empirically in experiments on a 3D rendered video dataset.
publication: '*UAI 2022 Workshop on Causal Representation Learning*'
links:
- name: URL
  url: https://openreview.net/forum?id=TpVzjh4M2hd
---
