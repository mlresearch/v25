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
pdf: "./trapeznikov12/trapeznikov12.pdf"
layout: inproceedings
key: trapeznikov12
month: 0
firstpage: 459
lastpage: 474
origpdf: http://jmlr.org/proceedings/papers/v25/trapeznikov12/trapeznikov12.pdf
sections: 
authors:
- given: K.
  family: Trapeznikov
- given: V.
  family: Saligrama
- given: !binary |-
    RC4gQ2FzdGF+bgA=
  family: 'on'
---
