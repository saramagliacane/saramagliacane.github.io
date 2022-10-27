---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Domain Adaptation by Using Causal Inference to Predict Invariant Conditional
  Distributions
subtitle: ''
summary: 'We show that can use labelled data in source domains and unlabelled data in the target domain to identify features that are robust to the specific shift that happens in the target dataset. While we use ideas from causality, we do not need to recover the causal graph (which in this case is not identifiable) to find these sets of features. '
authors:
- admin
- Thijs van Ommen
- Tom Claassen
- Stephan Bongers
- Philip Versteeg
- Joris M Mooij
tags: [Causality-inspired ML]
categories: []
date: '2018-01-01'
lastmod: 2022-10-27T12:56:28+02:00
featured: false
draft: false

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

url_pdf: 'https://proceedings.neurips.cc/paper/2018/file/39e98420b5e98bfbdc8a619bef7b8f61-Paper.pdf'
url_code: 'https://github.com/caus-am/dom_adapt'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: ''
#url_project: ''
url_slides: 'https://drive.google.com/file/d/1UHU9qZGCyZNQmQ_sGqjk53Il9w9PhZNx/view'
url_source: 'https://proceedings.neurips.cc/paper/2018/file/39e98420b5e98bfbdc8a619bef7b8f61-Paper.pdf'
url_video: 'https://www.youtube.com/watch?v=z748Lf4QTlE&feature=youtu.be'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Left'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-10-27T10:56:28.658483Z'
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
publication: 'Advances in Neural Processing Systems'
---


