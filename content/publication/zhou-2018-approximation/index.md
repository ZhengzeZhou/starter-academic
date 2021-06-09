---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Approximation trees: Statistical stability in model distillation'
subtitle: ''
summary: ''
authors:
- Yichen Zhou
- Zhengze Zhou
- Giles Hooker
tags: []
categories: []
date: '2018-01-01'
lastmod: 2021-06-07T23:34:16-04:00
featured: false
draft: false

url_pdf: 'https://arxiv.org/abs/1808.07573'

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
publishDate: '2021-06-08T03:34:16.365319Z'
publication_types:
- '3'
abstract: 'This paper examines the stability of learned explanations for black-box predictions via model distillation with decision trees. One approach to intelligibility in machine learning is to use an understandable 'student' model to mimic the output of an accurate 'teacher'. Here, we consider the use of regression trees as a student model, in which nodes of the tree can be used as 'explanations' for particular predictions, and the whole structure of the tree can be used as a global representation of the resulting function. However, individual trees are sensitive to the particular data sets used to train them, and an interpretation of a student model may be suspect if small changes in the training data have a large effect on it. In this context, access to outcomes from a teacher helps to stabilize the greedy splitting strategy by generating a much larger corpus of training examples than was originally available. We develop tests to ensure that enough examples are generated at each split so that the same splitting rule would be chosen with high probability were the tree to be re trained. Further, we develop a stopping rule to indicate how deep the tree should be built based on recent results on the variability of Random Forests when these are used as the teacher. We provide concrete examples of these procedures on the CAD-MDD and COMPAS data sets.'
publication: '*arXiv preprint arXiv:1808.07573*'
---
