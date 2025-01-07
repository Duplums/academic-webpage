---
title: 'UCSL: A Machine Learning Expectation-Maximization Framework for Unsupervised
  Clustering Driven by Supervised Learning'
authors:
- Robin Louiset
- Pietro Gori
- admin
- Josselin Houenou
- Antoine Grigis
- Edouard Duchesnay
date: '2021-01-01'
publishDate: '2024-12-29T17:27:10.736454Z'
publication_types:
- paper-conference
publication: '*Machine Learning and Knowledge Discovery in Databases -- ECML PKDD 2021*'
doi: 10.1007/978-3-030-86486-6_46
abstract: Subtype Discovery consists in finding interpretable and consistent sub-parts
  of a dataset, which are also relevant to a certain supervised task. From a mathematical
  point of view, this can be defined as a clustering task driven by supervised learning
  in order to uncover subgroups in line with the supervised prediction. In this paper,
  we propose a general Expectation-Maximization ensemble framework entitled UCSL (Unsupervised
  Clustering driven by Supervised Learning). Our method is generic, it can integrate
  any clustering method and can be driven by both binary classification and regression.
  We propose to construct a non-linear model by merging multiple linear estimators,
  one per cluster. Each hyperplane is estimated so that it correctly discriminates
  - or predict - only one cluster. We use SVC or Logistic Regression for classification
  and SVR for regression. Furthermore, to perform cluster analysis within a more suitable
  space, we also propose a dimension-reduction algorithm that projects the data onto
  an orthonormal space relevant to the supervised task. We analyze the robustness
  and generalization capability of our algorithm using synthetic and experimental
  datasets. In particular, we validate its ability to identify suitable consistent
  sub-types by conducting a psychiatric-diseases cluster analysis with known ground-truth
  labels. The gain of the proposed method over previous state-of-the-art techniques
  is about +1.9 points in terms of balanced accuracy. Finally, we make codes and examples
  available in a scikit-learn-compatible Python package.
tags:
- Clustering
- Expectation-maximization
- Machine learning
- Neuroimaging
- Subtype discovery
links:
- name: URL
  url: https://link.springer.com/chapter/10.1007/978-3-030-86486-6_46
url_pdf: https://link.springer.com/chapter/10.1007/978-3-030-86486-6_46
url_code: https://github.com/neurospin-projects/2021_rlouiset_ucsl
---
