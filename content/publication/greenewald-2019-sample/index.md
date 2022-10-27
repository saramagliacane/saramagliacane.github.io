---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Sample Efficient Active Learning of Causal Trees
subtitle: ''
summary: ''
authors:
- Kristjan Greenewald
- Dmitriy Katz
- Karthikeyan Shanmugam
- admin
- Murat Kocaoglu
- Enric Boix Adsera
- Guy Bresler
tags: 
  - intervention design
  - causal discovery
categories: []
date: '2019-01-01'
lastmod: 2022-10-27T14:52:04+02:00
featured: false
draft: false

url_pdf: 'https://proceedings.neurips.cc/paper/2019/file/5ee5605917626676f6a285fa4c10f7b0-Paper.pdf'
url_code: 'https://proceedings.neurips.cc/paper/2019/file/5ee5605917626676f6a285fa4c10f7b0-Supplemental.zip'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: 'https://drive.google.com/file/d/1UHU9qZGCyZNQmQ_sGqjk53Il9w9PhZNx/view'
url_source: 'https://proceedings.neurips.cc/paper/2019/hash/5ee5605917626676f6a285fa4c10f7b0-Abstract.html'
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
projects: interventionDesign
publishDate: '2022-10-27T12:52:03.889971Z'
publication_types:
- '1'
abstract: 'We consider the problem of experimental design for learning causal graphs that have a tree structure. We propose an adaptive framework that determines the next intervention based on a Bayesian prior updated with the outcomes of previous experiments, focusing on the setting where observational data is cheap (assumed infinite) and interventional data is expensive. While information greedy approaches are popular in active learning, we show that in this setting they can be exponentially suboptimal (in the number of interventions required), and instead propose an algorithm that exploits graph structure in the form of a centrality measure. If infinite interventional data is available, we show that the algorithm requires a number of interventions less than or equal to a factor of 2 times the minimum achievable number. We show that the algorithm and the associated theory can be adapted to the setting where each performed intervention yields finitely many samples. Several extensions are also presented, to the case where a specified set of nodes cannot be intervened on, to the case where K interventions are scheduled at once, and to the fully adaptive case where each experiment yields only one sample. In the case of finite interventional data, through simulated experiments we show that our algorithms outperform different adaptive baseline algorithms.'
publication: '*Advances in Neural Information Processing Systems*'
---
