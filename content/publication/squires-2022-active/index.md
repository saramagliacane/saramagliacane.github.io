---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Active Structure Learning of Causal DAGs via Directed Clique Trees
subtitle: ''
summary: ''
authors:
- Chandler Squires
- admin
- Kristjan Greenewald
- Dmitriy Katz
- Murat Kocaoglu
- Karthikeyan Shanmugam
tags: 
  - intervention design
  - causal discovery
categories: []
date: '2020-01-01'
lastmod: 2022-10-27T12:56:28+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

url_pdf: 'https://arxiv.org/pdf/2011.00641.pdf'
url_code: 'https://github.com/csquires/dct-policy'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: 'https://drive.google.com/file/d/1UHU9qZGCyZNQmQ_sGqjk53Il9w9PhZNx/view'
#url_source: 'https://proceedings.neurips.cc/paper/2018/file/39e98420b5e98bfbdc8a619bef7b8f61-Paper.pdf'
#url_video: 'https://www.youtube.com/watch?v=z748Lf4QTlE&feature=youtu.be'


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects: interventionDesign
publishDate: '2022-10-27T10:56:28.484212Z'
publication_types:
- '1'
abstract: A growing body of work has begun to study intervention design for efficient
  structure learning of causal directed acyclic graphs (DAGs). A typical setting is
  a causally sufficient setting, i.e. a system with no latent confounders, selection
  bias, or feedback, when the essential graph of the observational equivalence class
  (EC) is given as an input and interventions are assumed to be noiseless. Most existing
  works focus on worst-case or average-case lower bounds for the number of interventions
  required to orient a DAG. These worst-case lower bounds only establish that the
  largest clique in the essential graph could make it difficult to learn the true
  DAG. In this work, we develop a universal lower bound for singlenode interventions
  that establishes that the largest clique is always a fundamental impediment to structure
  learning. Specifically, we present a decomposition of a DAG into independently orientable
  components through directed clique trees and use it to prove that the number of
  single-node interventions necessary to orient any DAG in an EC is at least the sum
  of half the size of the largest cliques in each chain component of the essential
  graph. Moreover, we present a two-phase intervention design algorithm that, under
  certain conditions on the chordal skeleton, matches the optimal number of interventions
  up to a multiplicative logarithmic factor in the number of maximal cliques. We show
  via synthetic experiments that our algorithm can scale to much larger graphs than
  most of the related work and achieves better worst-case performance than other scalable
  approaches.
publication: '*Advances in Neural Information Processing Systems*'
---
