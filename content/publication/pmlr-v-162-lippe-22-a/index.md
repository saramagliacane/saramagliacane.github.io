---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "CITRIS: Causal Identifiability from Temporal Intervened Sequences"
subtitle: ''
summary: "In CITRIS we show under which conditions can one learn causal factors from sequences of high-dimensional data, e.g. images, in case one has access to the intervention targets. "
authors:
  - Phillip Lippe
  - admin
  - Sindy Löwe
  - Yuki M Asano
  - Taco Cohen
  - Stratis Gavves
tags: 
  - causal representation learning
  - CITRIS
categories: []
date: 2022-10-27T12:55:38+02:00
lastmod: 2022-10-27T12:55:38+02:00
featured: false
draft: false

url_pdf: 'https://proceedings.mlr.press/v162/lippe22a/lippe22a.pdf'
url_code: 'https://github.com/phlippe/CITRIS'
url_dataset: 'https://zenodo.org/record/6637749#.YqcWCnVBxCA'
url_poster: 'https://phlippe.github.io/media/CITRIS_Poster.pdf'
#url_project: 'CITRIS'
url_slides: 'https://phlippe.github.io/media/CITRIS_Slides.pdf'
url_source: 'https://proceedings.mlr.press/v162/lippe22a.html'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects: CITRIS

abstract: Understanding the latent causal factors of a dynamical system from visual observations is considered a crucial step towards agents reasoning in complex environments. In this paper, we propose CITRIS, a variational autoencoder framework that learns causal representations from temporal sequences of images in which underlying causal factors have possibly been intervened upon. In contrast to the recent literature, CITRIS exploits temporality and observing intervention targets to identify scalar and multidimensional causal factors, such as 3D rotation angles. Furthermore, by introducing a normalizing flow, CITRIS can be easily extended to leverage and disentangle representations obtained by already pretrained autoencoders. Extending previous results on scalar causal factors, we prove identifiability in a more general setting, in which only some components of a causal factor are affected by interventions. In experiments on 3D rendered image sequences, CITRIS outperforms previous methods on recovering the underlying causal variables. Moreover, using pretrained autoencoders, CITRIS can even generalize to unseen instantiations of causal factors, opening future research areas in sim-to-real generalization for causal representation learning.
publication: '*ICML 2022*'
---
