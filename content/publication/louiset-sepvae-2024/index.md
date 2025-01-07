---
title: 'SepVAE: a contrastive VAE to separate pathological patterns from healthy ones'
authors:
- Robin Louiset
- Edouard Duchesnay
- Antoine Grigis
- admin
- Pietro Gori
date: '2024-04-01'
publishDate: '2024-12-29T17:27:10.781381Z'
publication_types:
- conference-paper
publication: '*Medical Imaging for Deep Learning -- MIDL 2024*'
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
- Contrastive analysis
- Variational autoencoder
- Psychiatry
- Generative models 
links:
- name: URL
  url: https://openreview.net/forum?id=yLySzM5yxs
url_pdf: https://openreview.net/pdf?id=yLySzM5yxs
url_code: https://github.com/neurospin-projects/2023_rlouiset_sepvae
---
