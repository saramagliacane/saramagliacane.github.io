---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'AdaRL: What, Where, and How to Adapt in Transfer Reinforcement Learning'
subtitle: ''
summary: ''
authors:
- Biwei Huang
- Fan Feng
- Chaochao Lu
- admin
- Kun Zhang
tags: [causality-inspired ML]
categories: []
date: '2022-01-01'
lastmod: 2022-10-27T12:56:28+02:00
featured: false
draft: false

url_pdf: 'https://openreview.net/pdf?id=8H5bpVwvt5'
url_code: 'https://github.com/Adaptive-RL/AdaRL-code'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: 'https://drive.google.com/file/d/1UHU9qZGCyZNQmQ_sGqjk53Il9w9PhZNx/view'
url_source: 'https://openreview.net/forum?id=8H5bpVwvt5'
#url_video: 'https://www.youtube.com/watch?v=z748Lf4QTlE&feature=youtu.be'


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
projects: causalDomAdapt
publishDate: '2022-10-27T10:56:28.312237Z'
publication_types:
- '1'
abstract: One practical challenge in reinforcement learning (RL) is how to make quick
  adaptations when faced with new environments. In this paper, we propose a principled
  framework for adaptive RL, called textitAdaRL, that adapts reliably and efficiently
  to changes across domains with a few samples from the target domain, even in partially
  observable environments. Specifically, we leverage a parsimonious graphical representation
  that characterizes structural relationships over variables in the RL system. Such
  graphical representations provide a compact way to encode what and where the changes
  across domains are, and furthermore inform us with a minimal set of changes that
  one has to consider for the purpose of policy adaptation. We show that by explicitly
  leveraging this compact representation to encode changes, we can efficiently adapt
  the policy to the target domain, in which only a few samples are needed and further
  policy optimization is avoided. We illustrate the efficacy of AdaRL through a series
  of experiments that vary factors in the observation, transition, and reward functions
  for Cartpole and Atari games.
publication: '*International Conference on Learning Representations*'
---
