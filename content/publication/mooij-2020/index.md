---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Joint Causal Inference from Multiple Contexts
subtitle: ''
summary: 'We show that one can reduce a causal discovery problem on several different observational and experimental settings to a problem on a single distribution with the addition of several *context* variables. We call this approach *Joint Causal Inference* and show it can be combined with many algorithms, e.g. also algorithms that can deal with cycles, latent confounders and selection bias.'
authors:
- Joris M. Mooij
- admin
- Tom Claassen
tags:
- interventions
- causal inference
- randomized controlled trials
- observational and experimental data
- causal discovery
- causal modeling
categories: []
date: '2020-06-01'
lastmod: 2022-10-27T14:37:07+02:00
featured: false
draft: false

url_pdf: 'https://jmlr.csail.mit.edu/papers/volume21/17-123/17-123.pdf'
url_code: 'https://github.com/caus-am/jci'
#url_dataset: 'https://zenodo.org/record/6637749#.YqcWCnVBxCA'
#url_poster: ''
#url_project: ''
#url_slides: 'https://drive.google.com/file/d/1UHU9qZGCyZNQmQ_sGqjk53Il9w9PhZNx/view'
#url_source: 'https://proceedings.mlr.press/v162/lippe22a.html'
url_video: 'https://www.youtube.com/watch?v=NgxQkFwve70'

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
publishDate: '2022-10-27T12:37:07.125408Z'
publication_types:
- '2'
abstract: The gold standard for discovering causal relations is by means of experimentation.
  Over the last decades, alternative methods have been proposed that can infer causal
  relations between variables from certain statistical patterns in purely observational
  data. We introduce Joint Causal Inference (JCI), a novel approach to causal discovery
  from multiple data sets from different contexts that elegantly unifies both approaches.
  JCI is a causal modeling framework rather than a specific algorithm, and it can
  be implemented using any causal discovery algorithm that can take into account certain
  background knowledge. JCI can deal with different types of interventions (e.g.,
  perfect, imperfect, stochastic, etc.) in a unified fashion, and does not require
  knowledge of intervention targets or types in case of interventional data. We explain
  how several well-known causal discovery algorithms can be seen as addressing special
  cases of the JCI framework, and we also propose novel implementations that extend
  existing causal discovery methods for purely observational data to the JCI setting.
  We evaluate different JCI implementations on synthetic data and on ow cytometry
  protein expression data and conclude that JCI implementations can considerably outperform
  state-of-the-art causal discovery algorithms.
publication: '*J. Mach. Learn. Res.*'
---
