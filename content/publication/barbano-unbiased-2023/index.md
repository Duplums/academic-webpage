---
title: Unbiased Supervised Contrastive Learning
authors:
- Carlo Alberto Barbano
- Benoit Dufumier
- Enzo Tartaglione
- Marco Grangetto
- Pietro Gori
date: '2023-05-01'
publishDate: '2024-12-29T17:27:10.667436Z'
publication_types:
- paper-conference
publication: '*International Conference on Learning Representations – ICLR 2023*'
doi: 10.48550/arXiv.2211.05568
abstract: Many datasets are biased, namely they contain easy-to-learn features that
  are highly correlated with the target class only in the dataset but not in the true
  underlying distribution of the data. For this reason, learning unbiased models from
  biased data has become a very relevant research topic in the last years. In this
  work, we tackle the problem of learning representations that are robust to biases.
  We ﬁrst present a margin-based theoretical framework that allows us to clarify why
  recent contrastive losses (InfoNCE, SupCon, etc.) can fail when dealing with biased
  data. Based on that, we derive a novel formulation of the supervised contrastive
  loss ( -SupInfoNCE), providing more accurate control of the minimal distance between
  positive and negative samples. Furthermore, thanks to our theoretical framework,
  we also propose FairKL, a new debiasing regularization loss, that works well even
  with extremely biased data. We validate the proposed losses on standard vision datasets
  including CIFAR10, CIFAR100, and ImageNet, and we assess the debiasing capability
  of FairKL with -SupInfoNCE, reaching stateof-the-art performance on a number of
  biased datasets, including real instances of biases “in the wild”.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2211.05568
---
