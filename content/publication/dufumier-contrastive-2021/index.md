---
title: Contrastive Learning with Continuous Proxy Meta-data for 3D MRI Classification
authors:
- Benoit Dufumier
- Pietro Gori
- Julie Victor
- Antoine Grigis
- Michele Wessa
- Paolo Brambilla
- Pauline Favre
- Mircea Polosan
- Colm McDonald
- Camille Marie Piguet
- Mary Phillips
- Lisa Eyler
- Edouard Duchesnay
date: '2021-01-01'
publishDate: '2024-12-29T16:52:30.229334Z'
publication_types:
- paper-conference
publication: '*Medical Image Computing and Computer Assisted Intervention – MICCAI
  2021*'
doi: 10.1007/978-3-030-87196-3_6
abstract: 'Traditional supervised learning with deep neural networks requires a tremendous
  amount of labelled data to converge to a good solution. For 3D medical images, it
  is often impractical to build a large homogeneous annotated dataset for a specific
  pathology. Self-supervised methods offer a new way to learn a representation of
  the images in an unsupervised manner with a neural network. In particular, contrastive
  learning has shown great promises by (almost) matching the performance of fully-supervised
  CNN on vision tasks. Nonetheless, this method does not take advantage of available
  meta-data, such as participant’s age, viewed as prior knowledge. Here, we propose
  to leverage continuous proxy metadata, in the contrastive learning framework, by
  introducing a new loss called y-Aware InfoNCE loss. Specifically, we improve the
  positive sampling during pre-training by adding more positive examples with similar
  proxy meta-data with the anchor, assuming they share similar discriminative semantic
  features. With our method, a 3D CNN model pre-trained on $$10textasciicircum4$$104multi-site
  healthy brain MRI scans can extract relevant features for three classification tasks:
  schizophrenia, bipolar diagnosis and Alzheimer’s detection. When fine-tuned, it
  also outperforms 3D CNN trained from scratch on these tasks, as well as state-of-the-art
  self-supervised methods. Our code is made publicly available here.'
---
