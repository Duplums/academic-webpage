---
title: Integrating Prior Knowledge in Contrastive Learning with Kernel
authors:
- Benoit Dufumier
- Carlo Alberto Barbano
- Robin Louiset
- Edouard Duchesnay
- Pietro Gori
date: '2023-07-01'
publishDate: '2024-12-29T17:27:10.713426Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 40th International Conference on Machine Learning
  – ICML 2023*'
abstract: Data augmentation is a crucial component in unsupervised contrastive learning
  (CL). It determines how positive samples are defined and, ultimately, the quality
  of the learned representation. In this work, we open the door to new perspectives
  for CL by integrating prior knowledge, given either by generative models - viewed
  as prior representations - or weak attributes in the positive and negative sampling.
  To this end, we use kernel theory to propose a novel loss, called decoupled uniformity,
  that i) allows the integration of prior knowledge and ii) removes the positive-negative
  coupling in the original InfoNCE loss. We draw a connection between contrastive
  learning and the conditional mean embedding theory to derive tight bounds on the
  downstream classification loss. In an unsupervised setting, we empirically demonstrate
  that CL benefits from generative models to improve its representation both on natural
  and medical images. In a weakly supervised scenario, our framework outperforms other
  unconditional and conditional CL approaches.
links:
- name: URL
  url: https://proceedings.mlr.press/v202/dufumier23a.html
---
