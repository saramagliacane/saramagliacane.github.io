---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Domain Adaptation by Using Causal Inference to Predict Invariant Conditional
  Distributions
subtitle: ''
summary: ''
authors:
- Sara Magliacane
- Thijs van Ommen
- Tom Claassen
- Stephan Bongers
- Philip Versteeg
- Joris M Mooij
tags: [causality-inspired ML]
categories: []
date: '2018-01-01'
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

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-10-27T10:56:28.658483Z'
publication_types:
- '1'
abstract: An important goal common to domain adaptation and causal inference is to
  make accurate predictions when the distributions for the source (or training) domain(s)
  and target (or test) domain(s) differ. In many cases, these different distributions
  can be modeled as different contexts of a single underlying system, in which each
  distribution corresponds to a different perturbation of the system, or in causal
  terms, an intervention. We focus on a class of such causal domain adaptation problems,
  where data for one or more source domains are given, and the task is to predict
  the distribution of a certain target variable from measurements of other variables
  in one or more target domains. We propose an approach for solving these problems
  that exploits causal inference and does not rely on prior knowledge of the causal
  graph, the type of interventions or the intervention targets. We demonstrate our
  approach by evaluating a possible implementation on simulated and real world data.
publication: 'NeurIPS 2018'
---
