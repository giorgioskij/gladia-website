---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multi-Source Diffusion Models for Simultaneous Music Generation and Separation
subtitle: ''
summary: ''
authors:
- mariani
- tallini
- postolache
- mancusi
- cosmo
- rodola
tags:
- Signal Processing
- Music Generation
- Source Separation
- 'featured'
categories: []
date: '2024-06-03'
lastmod: 2024-05-05T14:00:41+01:00
featured: true
draft: false
publication_short: "ICLR 2024"

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
publishDate: '2024-05-05T14:00:41.136745Z'
publication_types:
- '1'
abstract: 'In this work, we define a diffusion-based generative model capable of both music synthesis and source separation by learning the score of the joint probability density of sources sharing a context. Alongside the classic total inference tasks (i.e., generating a mixture, separating the sources), we also introduce and experiment on the partial generation task of source imputation, where we generate a subset of the sources given the others (e.g., play a piano track that goes well with the drums). Additionally, we introduce a novel inference method for the separation task based on Dirac likelihood functions. We train our model on Slakh2100, a standard dataset for musical source separation, provide qualitative results in the generation settings, and showcase competitive quantitative results in the source separation setting. Our method is the first example of a single model that can handle both generation and separation tasks, thus representing a step toward general audio models.'
publication: '*International Conference on Learning Representations (ICLR 2024)*'
links:
- name: 'PDF'
  url: https://openreview.net/pdf?id=h922Qhkmx1
- icon: link
  icon_pack: fas
  name: 'URL'
  url: https://openreview.net/forum?id=h922Qhkmx1
- name: 'arXiv'
  url: https://arxiv.org/abs/2302.02257
- icon: github
  icon_pack: fab
  name: 'GitHub'
  url: https://github.com/gladia-research-group/multi-source-diffusion-models
- icon: award
  icon_pack: fas
  name: 'ICLR 2024 notable top 1.2% (oral)'
  url: https://iclr.cc/virtual/2024/poster/18110
---
