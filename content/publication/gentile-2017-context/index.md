---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "On context-dependent clustering of bandits"
subtitle: ''

abstract: We investigate a novel cluster-of-bandit algorithm CAB for collaborative recommendation tasks that implements the underlying feedback sharing mechanism by estimating the neighborhood of users in a context-dependent manner. CAB makes sharp departures from the state of the art by incorporating collaborative effects into inference as well as learning processes in a manner that seamlessly interleaving explore-exploit tradeoffs and collaborative steps. We prove regret bounds under various assumptions on the data, which exhibit a crisp dependence on the expected number of clusters over the users, a natural measure of the statistical difficulty of the learning task. Experiments on production and real-world datasets show that CAB offers significantly increased prediction performance against a representative pool of state-of-the-art methods.

authors:
- Claudio Gentile
- Shuai Li
- Purushottam Kar
- Alexandros Karatzoglou
- Giovanni Zappella
- Evans Etrue
tags: []
categories: []
date: '2017-01-01'
lastmod: 2021-02-06T21:41:42+01:00
featured: true
draft: true

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
publishDate: '2021-02-06T20:41:37.397406Z'
publication_types: 
- '1'
abstract: 'We investigate a novel cluster-of-bandit algorithm CAB for collaborative recommendation
tasks that implements the underlying feedback sharing mechanism by estimating user neighborhoods in a context-dependent manner. CAB makes sharp departures from the state of the art by incorporating collaborative effects into inference, as well as learning processes in a manner
that seamlessly interleaves explore-exploit tradeoffs and collaborative steps. We prove regret bounds for CAB under various data-dependent assumptions which exhibit a crisp dependence on the expected number of clusters over the users, a natural measure of the statistical difficulty of the learning task. Experiments on production and
real-world datasets show that CAB offers significantly increased prediction performance against a representative pool of state-of-the-art methods.
'
publication: '*International Conference on Machine Learning*'
publication_short: PMLR

url_pdf: 'http://proceedings.mlr.press/v70/gentile17a/gentile17a.pdf'

projects:
- example
---
