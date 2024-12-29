---
title: MixUp Brain-Cortical Augmentations in Self-supervised Learning
authors:
- Corentin Ambroise
- Vincent Frouin
- Benoit Dufumier
- Edouard Duchesnay
- Antoine Grigis
date: '2023-01-01'
publishDate: '2024-12-29T17:27:10.744078Z'
publication_types:
- paper-conference
publication: '*Machine Learning in Clinical Neuroimaging*'
doi: 10.1007/978-3-031-44858-4_10
abstract: 'Learning biological markers for a specific brain pathology is often impaired
  by the size of the dataset. With the advent of large open datasets in the general
  population, new learning strategies have emerged. In particular, deep representation
  learning consists of training a model via pretext tasks that can be used to solve
  downstream clinical problems of interest. More recently, self-supervised learning
  provides a rich framework for learning representations by contrasting transformed
  samples. These methods rely on carefully designed data manipulation to create semantically
  similar but syntactically different samples. In parallel, domain-specific architectures
  such as spherical convolutional neural networks can learn from cortical brain measures
  in order to reveal original biomarkers. Unfortunately, only a few surface-based
  augmentations exist, and none of them have been applied in a self-supervised learning
  setting. We perform experiments on two open source datasets: Big Healthy Brain and
  Healthy Brain Network. We propose new augmentations for the cortical brain: baseline
  augmentations adapted from classical ones for training convolutional neural networks,
  typically on natural images, and new augmentations called MixUp. The results suggest
  that surface-based self-supervised learning performs comparably to supervised baselines,
  but generalizes better to different tasks and datasets. In addition, the learned
  representations are improved by the proposed MixUp augmentations. The code is available
  on GitHub (https://github.com/neurospin-projects/2022_cambroise_surfaugment).'
tags:
- Brain structural MRI
- Data augmentation
- Self-supervised learning
- Spherical convolutional neural networks
---
