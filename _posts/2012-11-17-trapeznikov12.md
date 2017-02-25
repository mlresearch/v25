---
title: Multi-Stage Classifier Design
abstract: In many classification systems, sensing modalities have different acquisition
  costs. It is often unnecessary to use every modality to classify a majority of examples.
  We study a multi-stage system in a prediction time cost reduction setting, where
  the full data is available for training, but for a test example, measurements in
  a new modality can be acquired at each stage for an additional cost. We seek decision
  rules to reduce the average measurement acquisition cost. We formulate an empirical
  risk minimization problem (ERM) for a multi-stage reject classifier, wherein the
  stage k classifier either classifies a sample using only the measurements acquired
  so far or rejects it to the next stage where more attributes can be acquired for
  a cost. To solve the ERM problem, we factorize the cost function into classification
  and rejection decisions. We then transform reject decisions into a binary classification
  problem. We construct stage-by-stage global surrogate risk, develop an iterative
  algorithm in the boosting framework and present convergence results. We test our
  work on synthetic, medical and explosives detection datasets. Our results demonstrate
  that substantial cost reduction without a significant sacrifice in accuracy is achievable.
pdf: http://proceedings.mlr.press/v25/trapeznikov12/trapeznikov12.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: trapeznikov12
month: 0
tex_title: Multi-Stage Classifier Design
firstpage: 459
lastpage: 474
page: 459-474
sections: 
author:
- given: K.
  family: Trapeznikov
- given: V.
  family: Saligrama
- given: !binary |-
    RC4gQ2FzdGHCoG4A
  family: 'on'
date: 2012-11-17
address: Singapore Management University, Singapore
publisher: PMLR
container-title: Proceedings of the Asian Conference on Machine Learning
volume: '25'
genre: inproceedings
issued:
  date-parts:
  - 2012
  - 11
  - 17
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
