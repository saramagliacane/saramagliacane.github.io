---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Verifiably safe exploration for end-to-end reinforcement learning
subtitle: ''
summary: ''
authors:
- Nathan Hunt
- Nathan Fulton
- admin
- Trong Nghia Hoang
- Subhro Das
- Armando Solar-Lezama
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-10-27T14:52:04+02:00
featured: false
draft: false



url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3447928.3456653'
url_code: 'https://github.com/IBM/vsrl-framework'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: 'https://drive.google.com/file/d/1UHU9qZGCyZNQmQ_sGqjk53Il9w9PhZNx/view'
url_source: 'https://dl.acm.org/doi/abs/10.1145/3447928.3456653'
url_video: 'https://www.youtube.com/watch?v=VzUVLXWixuQ'





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
publishDate: '2022-10-27T12:52:04.060808Z'
publication_types:
- '1'
abstract: 
  Deploying deep reinforcement learning in safety-critical settings requires developing algorithms that obey hard constraints during exploration. This paper contributes a first approach toward enforcing formal safety constraints on end-to-end policies with visual inputs. Our approach draws on recent advances in object detection and automated reasoning for hybrid dynamical systems. The approach is evaluated on a novel benchmark that emphasizes the challenge of safely exploring in the presence of hard constraints. Our benchmark draws from several proposed problem sets for safe learning and includes problems that emphasize challenges such as reward signals that are not aligned with safety constraints. On each of these benchmark problems, our algorithm completely avoids unsafe behavior while remaining competitive at optimizing for as much reward as is safe. We also prove that our method of enforcing the safety constraints preserves all safe policies from the original environment.
publication: '*Proceedings of the 24th International Conference on Hybrid Systems:
  Computation and Control*'
---
