---
title: 'Benchmarking CNN on 3D Anatomical Brain MRI: Architectures, Data Augmentation
  and Deep Ensemble Learning'
authors:
- admin
- Pietro Gori
- Ilaria Battaglia
- Julie Victor
- Antoine Grigis
- Edouard Duchesnay
date: '2023-04-01'
publishDate: '2024-12-29T17:27:10.674892Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2106.01132
abstract: 'Deep Learning (DL) and speciﬁcally CNN models have become a de facto method
  for a wide range of vision tasks, outperforming traditional machine learning (ML)
  methods. Consequently, they drew a lot of attention in the neuroimaging ﬁeld in
  particular for phenotype prediction or computer-aided diagnosis. However, most of
  the current studies often deal with small single-site cohorts, along with a speciﬁc
  pre-processing pipeline and custom CNN architectures, which make them difﬁcult to
  compare to. We propose an extensive benchmark of recent state-of-the-art (SOTA)
  3D CNN, evaluating also the beneﬁts of data augmentation and deep ensemble learning,
  on both Voxel-Based Morphometry (VBM) pre-processing and minimally preprocessed
  quasi-raw images. Experiments were conducted on a large heterogeneous multi-site
  3D brain anatomical MRI data-set comprising N = 10k scans on 3 challenging tasks:
  age prediction, sex classiﬁcation, and schizophrenia diagnosis. We found that all
  models provide signiﬁcantly better predictions with VBM images than quasi-raw data.
  This ﬁnding evolved as the training set approaches 10k samples where quasi-raw data
  almost reach the performance of VBM. Moreover, we showed that linear models perform
  comparably with SOTA CNN on VBM data. We also demonstrated that DenseNet and tiny-DenseNet,
  a lighter version that we proposed, provide a good compromise in terms of performance
  in all data regime. Therefore, we suggest to employ them as the architectures by
  default. Critically, we also showed that current CNN are still very biased towards
  the acquisition site, even when trained with N = 10k multi-site images. In this
  context, VBM pre-processing provides an efﬁcient way to limit this site effect.
  Surprisingly, we did not ﬁnd any clear beneﬁt from data augmentation techniques
  - and more recently proposed MRI artefacts for brain MRI. Finally, we also showed
  that big CNN models were not well calibrated when trained with small brain MRI data-sets
  and we empirically proved that deep ensemble learning is well suited to re-calibrate
  them without sacriﬁcing performance.'
tags:
- Brain imaging
- Deep learning
- Pychiatric disorders
- Brain age prediction
links:
- name: URL
  url: http://arxiv.org/abs/2106.01132
---
