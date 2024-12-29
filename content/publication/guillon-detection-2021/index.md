---
title: Detection of Abnormal Folding Patterns with Unsupervised Deep Generative Models
authors:
- Louise Guillon
- Bastien Cagna
- Benoit Dufumier
- Joël Chavas
- Denis Rivière
- Jean-François Mangin
date: '2021-01-01'
publishDate: '2024-12-29T17:27:10.729312Z'
publication_types:
- paper-conference
publication: '*Machine Learning in Clinical Neuroimaging*'
doi: 10.1007/978-3-030-87586-2_7
abstract: Although the main structures of cortical folding are present in each human
  brain, the folding pattern is unique to each individual. Because of this large normal
  variability, the identification of abnormal patterns associated to developmental
  disorders is a complex open challenge. In this paper, we tackle this problem as
  an anomaly detection task and explore the potential of deep generative models using
  benchmarks made up of synthetic anomalies. To focus learning on the folding geometry,
  brain MRI are preprocessed first to deal only with a skeleton-based negative cast
  of the cortex. A variational auto-encoder is trained to get a representation of
  the regional variability of the folding pattern of the general population. Then
  several synthetic benchmark datasets of abnormalities are designed. The latent space
  expressivity is assessed through classification experiments between control’s and
  abnormal’s latent codes. Finally, the properties encoded in the latent space are
  analyzed through perturbation of specific latent dimensions and observation of the
  resulting modification of the reconstructed images. The results have shown that
  the latent representation is rich enough to distinguish subtle differences like
  asymmetries between the right and left hemispheres.
tags:
- Anomaly benchmark
- Anomaly detection
- Brain architecture
- Cortical folding
- Variational autoencoder
---
