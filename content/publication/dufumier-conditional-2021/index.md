---
title: Conditional Alignment and Uniformity for Contrastive Learning with Continuous
  Proxy Labels
authors:
- admin
- Pietro Gori
- Julie Victor
- Antoine Grigis
- Edouard Duchesnay
date: '2021-11-01'
publishDate: '2024-12-29T17:27:10.702257Z'
publication_types:
- paper-conference
publication: '*Medical Imaging Meets NeurIPS Workshop 2021*'
doi: 10.48550/arXiv.2111.05643
abstract: 'Contrastive Learning has shown impressive results on natural and medical
  images, without requiring annotated data. However, a particularity of medical images
  is the availability of meta-data (such as age or sex) that can be exploited for
  learning representations. Here, we show that the recently proposed contrastive y-Aware
  InfoNCE loss, that integrates multi-dimensional meta-data, asymptotically optimizes
  two properties: conditional alignment and global uniformity. Similarly to [33],
  conditional alignment means that similar samples should have similar features, but
  conditionally on the meta-data. Instead, global uniformity means that the (normalized)
  features should be uniformly distributed on the unit hypersphere, independently
  of the meta-data. Here, we propose to deﬁne conditional uniformity, relying on the
  meta-data, that repel only samples with dissimilar metadata. We show that direct
  optimization of both conditional alignment and uniformity improves the representations,
  in terms of linear evaluation, on both CIFAR-100 and a brain MRI dataset.'
tags:
- Contrastive Learning
- Weakly Supervised Learning
- Brain imaging
links:
- name: URL
  url: https://neurips.cc/virtual/2021/40536
url_pdf: 'http://arxiv.org/abs/2111.05643'
url_code: 'https://github.com/EIDOSLAB/unbiased-contrastive-learning'
url_poster: 'https://neurips.cc/virtual/2021/40536'
url_slides: 'https://neurips.cc/virtual/2021/40536'
---
