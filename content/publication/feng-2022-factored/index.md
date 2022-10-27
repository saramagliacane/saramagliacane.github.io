---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Factored Adaptation for Non-Stationary Reinforcement Learning
subtitle: ''
summary: ''
authors:
- Fan Feng
- Biwei Huang
- Kun Zhang
- admin
tags: [Causality-inspired ML]
categories: []
date: '2022-01-01'
lastmod: 2022-10-27T12:55:38+02:00
featured: false
draft: false

url_pdf: 'https://arxiv.org/pdf/2203.16582.pdf'
url_code: 'https://github.com/ffeng1996/Factored-Nonstationary-RL'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: 'https://drive.google.com/file/d/1UHU9qZGCyZNQmQ_sGqjk53Il9w9PhZNx/view'
url_source: 'https://arxiv.org/abs/2203.16582'
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
projects: []
publishDate: '2022-10-27T10:55:38.596565Z'
publication_types:
- '1'
abstract: Dealing with non-stationarity in environments (e.g., in the transition dynamics)
  and objectives (e.g., in the reward functions) is a challenging problem that is
  crucial in real-world applications of reinforcement learning (RL). While most current
  approaches model the changes as a single shared embedding vector, we leverage insights
  from the recent causality literature to model non-stationarity in terms of individual
  latent change factors, and causal graphs across different environments. In particular,
  we propose Factored Adaptation for Non-Stationary RL (FANS-RL), a factored adaption
  approach that learns jointly both the causal structure in terms of a factored MDP,
  and a factored representation of the individual time-varying change factors. We
  prove that under standard assumptions, we can completely recover the causal graph
  representing the factored transition and reward function, as well as a partial structure
  between the individual change factors and the state components. Through our general
  framework, we can consider general non-stationary scenarios with different function
  types and changing frequency, including changes across episodes and within episodes.
  Experimental results demonstrate that FANS-RL outperforms existing approaches in
  terms of return, compactness of the latent state representation, and robustness
  to varying degrees of non-stationarity.
publication: '*Advances in Neural Information Processing Systems*'
doi: 10.48550/ARXIV.2203.16582
---
