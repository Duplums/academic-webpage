---
title: 'Exploring the potential of representation and transfer learning for anatomical
  neuroimaging: Application to psychiatry'
authors:
- admin
- Pietro Gori
- Sara Petiton
- Robin Louiset
- Jean-François Mangin
- Antoine Grigis
- Edouard Duchesnay
date: '2024-08-01'
publishDate: '2024-12-29T17:27:10.720230Z'
publication_types:
- article-journal
publication: '*NeuroImage*'
doi: 10.1016/j.neuroimage.2024.120665
abstract: 'The perspective of personalized medicine for brain disorders requires efficient
  learning models for anatomical neuroimaging-based prediction of clinical conditions.
  There is now a consensus on the benefit of deep learning (DL) in addressing many
  medical imaging tasks, such as image segmentation. However, for single-subject prediction
  problems, recent studies yielded contradictory results when comparing DL with Standard
  Machine Learning (SML) on top of classical feature extraction. Most existing comparative
  studies were limited in predicting phenotypes of little clinical interest, such
  as sex and age, and using a single dataset. Moreover, they conducted a limited analysis
  of the employed image pre-processing and feature selection strategies. This paper
  extensively compares DL and SML prediction capacity on five multi-site problems,
  including three increasingly complex clinical applications in psychiatry namely
  schizophrenia, bipolar disorder, and Autism Spectrum Disorder (ASD) diagnosis. To
  compensate for the relative scarcity of neuroimaging data on these clinical datasets,
  we also evaluate three pre-training strategies for transfer learning from brain
  imaging of the general healthy population: self-supervised learning, generative
  modeling and supervised learning with age. Overall, we find similar performance
  between randomly initialized DL and SML for the three clinical tasks and a similar
  scaling trend for sex prediction. This was replicated on an external dataset. We
  also show highly correlated discriminative brain regions between DL and linear ML
  models in all problems. Nonetheless, we demonstrate that self-supervised pre-training
  on large-scale healthy population imaging datasets (N≈10k), along with Deep Ensemble,
  allows DL to learn robust and transferable representations to smaller-scale clinical
  datasets (N≤1k). It largely outperforms SML on 2 out of 3 clinical tasks both in
  internal and external test sets. These findings suggest that the improvement of
  DL over SML in anatomical neuroimaging mainly comes from its capacity to learn meaningful
  and useful abstract representations of the brain anatomy, and it sheds light on
  the potential of transfer learning for personalized medicine in psychiatry'
tags:
- Anatomical neuroimaging
- Deep learning
- Individual subject prediction
- Machine learning
- Psychiatric disorders
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1053811924001605
url_pdf: https://www.sciencedirect.com/science/article/pii/S1053811924001605
url_code: 'https://github.com/Duplums/SMLvsDL'
url_dataset: 'https://ieee-dataport.org/open-access/openbhb-multi-site-brain-mri-dataset-age-prediction-and-debiasing'
featured: true

image:
  preview_only: false

---
