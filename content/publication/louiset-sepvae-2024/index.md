---
title: 'SepVAE: a contrastive VAE to separate pathological patterns from healthy ones'
authors:
- Robin Louiset
- Edouard Duchesnay
- Antoine Grigis
- Benoit Dufumier
- Pietro Gori
date: '2024-04-01'
publishDate: '2024-12-29T17:27:10.781381Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2307.06206
abstract: 'Contrastive Analysis VAE (CA-VAEs) is a family of Variational auto-encoders
  (VAEs) that aims at separating the common factors of variation between a background
  dataset (BG) (i.e., healthy subjects) and a target dataset (TG) (i.e., patients)
  from the ones that only exist in the target dataset. To do so, these methods separate
  the latent space into a set of salient features (i.e., proper to the target dataset)
  and a set of common features (i.e., exist in both datasets). Currently, all models
  fail to prevent the sharing of information between latent spaces effectively and
  to capture all salient factors of variation. To this end, we introduce two crucial
  regularization losses: a disentangling term between common and salient representations
  and a classification term between background and target samples in the salient space.
  We show a better performance than previous CA-VAEs methods on three medical applications
  and a natural images dataset (CelebA). Code and datasets are available on GitHub
  https: //github.com/neurospin-projects/ 2023_rlouiset_sepvae.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2307.06206
---
