---
title: 'OpenBHB: a Large-Scale Multi-Site Brain MRI Data-set for Age Prediction and
  Debiasing'
authors:
- admin
- Antoine Grigis
- Julie Victor
- Corentin Ambroise
- Vincent Frouin
- Edouard Duchesnay
date: '2022-11-01'
publishDate: '2024-12-29T17:27:10.659582Z'
publication_types:
- article-journal
publication: '*NeuroImage*'
doi: 10.1016/j.neuroimage.2022.119637
abstract: 'Prediction of chronological age from neuroimaging in the healthy population
  is an important issue because the deviations from normal brain age may highlight
  abnormal trajectories towards brain disorders. As a first step, ML models have emerged
  to predict chronological age from brain MRI, as a proxy measure of biological age.
  However, there is currently no consensus w.r.t. which Machine Learning (ML) model
  is best suited for this task, largely because of a lack of public benchmark. Furthermore,
  new large emerging population neuroimaging datasets are often biased by the acquisition
  center images are coming from. This bias heavily deteriorates models generalization
  capacities, especially for Deep Learning (DL) algorithms that are known to overfit
  rapidly on the simplest features (known as simplicity bias). Here we propose a new
  public benchmarking resource, namely Open Big Healthy Brains (OpenBHB), along with
  a challenge for both brain age prediction and site-effect removal through a representation
  learning framework. OpenBHB is large-scale, gathering 5K+ 3D T1 brain
  MRI from Healthy Controls (HC) and highly multi-sites, aggregating 60+
  centers worldwide and 10 studies. OpenBHB is expected to grow both in terms of available
  modalities and number of subjects. All OpenBHB datasets are uniformly preprocessed,
  including quality check, with container technologies that consist in: 3D Voxel-Based
  Morphometry maps (VBM from CAT12), quasi-raw (simple linear alignment of images),
  and Surface-Based Morphometry indices (SBM, from FreeSurfer). The OpenBHB challenge
  is permanent and we provide all tools, materials and tutorials for participants
  to easily submit and benchmark their model against each other on a public leaderboard.'
tags:
- Brain age prediction
- Machine learning
- MRI
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1053811922007522
url_pdf: https://www.sciencedirect.com/science/article/pii/S1053811922007522
url_code: 'https://github.com/ramp-kits/brain_age_with_site_removal'
url_dataset: 'https://ieee-dataport.org/open-access/openbhb-multi-site-brain-mri-dataset-age-prediction-and-debiasing'
---
