---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Learning Dynamic Attribute-factored World Models for Efficient Multi-object Reinforcement Learning
subtitle: ''
summary: ''
authors:
- Fan Feng
- admin
tags: 
  - causality-inspired ML
categories: []
date: '2023-03-01'
lastmod: 2023-09-21T14:52:04+02:00
featured: false
draft: false

url_pdf: 'https://arxiv.org/pdf/2307.09205.pdf'
#url_code: 'https://github.com/yongtuoliu/Graph-Switching-Dynamical-Systems'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: 'https://icml.cc/media/PosterPDFs/ICML%202023/24872.png?t=1689664913.4659803'
#url_project: 'https://phlippe.github.io/BISCUIT/'
#url_slides: 'https://phlippe.github.io/media/BISCUIT_Slides.pdf'
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
publishDate: '2023-9-22T12:52:04.227349Z'
publication_types:
- '1'
abstract: 
  'In many reinforcement learning tasks, the agent has to learn to interact with many
objects of different types and generalize to unseen combinations and numbers
of objects. Often a task is a composition of previously learned tasks (e.g. block
stacking). These are examples of compositional generalization, in which we
compose object-centric representations to solve complex tasks. Recent works have
shown the benefits of object-factored representations and hierarchical abstractions
for improving sample efficiency in these settings. On the other hand, these methods
do not fully exploit the benefits of factorization in terms of object attributes. In this
paper, we address this opportunity and introduce the Dynamic Attribute FacTored
RL (DAFT-RL) framework. In DAFT-RL, we leverage object-centric representation
learning to extract objects from visual inputs. We learn to classify them in classes
and infer their latent parameters. For each class of object, we learn a class template
graph that describes how the dynamics and reward of an object of this class factorize
according to its attributes. We also learn an interaction pattern graph that describes
how objects of different classes interact with each other at the attribute level.
Through these graphs and a dynamic interaction graph that models the interactions
between objects, we can learn a policy that can then be directly applied in a new
environment by just estimating the interactions and latent parameters. We evaluate
DAFT-RL in three benchmark datasets and show our framework outperforms the
state-of-the-art in generalizing across unseen objects with varying attributes and
latent parameters, as well as in the composition of previously learned tasks.'
publication: '*NeurIPS 2023*'
links:
- name: URL
  url: https://arxiv.org/pdf/2307.09205.pdf
---
