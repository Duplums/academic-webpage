---
title: How and Why Does Deep Ensemble Coupled with Transfer Learning Increase Performance
  in Bipolar Disorder and Schizophrenia Classification?
authors:
- Sara Petiton
- Antoine Grigis
- admin
- Edouard Duchesnay
date: '2024-05-01'
publishDate: '2024-12-29T17:27:10.773674Z'
publication_types:
- paper-conference
publication: '*IEEE International Symposium on Biomedical Imaging -- ISBI 2024*'
doi: 10.1109/ISBI56570.2024.10635777
abstract: Transfer learning (TL) and deep ensemble learning (DE) have recently been
  shown to outperform simple machine learning in classifying psychiatric disorders.
  However, there is still a lack of understanding as to why that is. This paper aims
  to understand how and why DE and TL reduce the variability of single-subject classification
  models in bipolar disorder (BD) and schizophrenia (SCZ). To this end, we investigated
  the training stability of TL and DE models. For the two classification tasks under
  consideration, we compared the results of multiple trainings with the same backbone
  but with different initializations. In this way, we take into account the epistemic
  uncertainty associated with the uncertainty in the estimation of the model parameters.
  It has been shown that the performance of classifiers can be significantly improved
  by using TL with DE. Based on these results, we investigate i) how many models are
  needed to benefit from the performance improvement of DE when classifying BD and
  SCZ from healthy controls, and ii) how TL induces better generalization, with and
  without DE. In the first case, we show that DE reaches a plateau when 10 models
  are included in the ensemble. In the second case, we find that using a pre-trained
  model constrains TL models with the same pre-training to stay in the same basin
  of the loss function. This is not the case for DL models with randomly initialized
  weights. 1
tags:
- bipolar disorder
- brain anatomical MRI
- deep ensemble learning
- deep learning
- Interpolation
- Mental disorders
- Predictive models
- schizophrenia
- Solid modeling
- Training
- transfer learning
- Transfer learning
- Uncertainty
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10635777
url_pdf: https://ieeexplore.ieee.org/iel8/10635099/10635102/10635777.pdf
url_code: https://github.com/SaraMPetiton/DE_with_TL_study
---
