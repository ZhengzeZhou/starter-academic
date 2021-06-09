---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SILR: A New Exact Test for Demonstrating That an Effect Exists in Binary Trials'
subtitle: ''
summary: ''
authors:
- Zhengze Zhou
- Richard B Darlington
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-06-07T23:34:17-04:00
featured: false
draft: false

url_pdf: 'https://psyarxiv.com/4u5yc/'
url_code: 'https://github.com/ZhengzeZhou/SILR'

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
publishDate: '2021-06-08T03:34:17.039554Z'
publication_types:
- '3'
abstract: 'Suppose N experimental participants each undergo t binary trials, and you want to show that at least some of the participants have higher success rates than would be expected if the true success rate for all participants on all trials were the same known value pnull. Under broad circumstances, a new test called SILR has substantially higher power than six other tests that might be used for this purpose. In one example, SILR yielded a significance level of 0.0032 while the other six tests all yielded values above 0.05. In one power analysis, SILR’s power exceeded that of the standard binomial test, applied to the results of all trials for all participants, even when the sample size for SILR was less than 30% that for the binomial.  
We provide a free R program for SILR. It can also find confidence limits on the number of experimental participants whose true hit rate exceeds the null value, and on the highest and lowest true hit rates of any participants. SILR does not show conclusively that any particular participant’s true hit rate differs significantly from the null rate. If such tests are desired, that can be done with Bonferroni-corrected binomial tests on individual participants. But SILR often has much higher power than these tests.'
publication: '*PsyArXiv*'
---
