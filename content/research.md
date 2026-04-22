---
title: "research"
date: 2026-04-22
---

## in brief

We develop statistical and machine learning methods for complex biomedical data, with a particular focus on uncertainty quantification, robust inference, and prediction in settings where the scientific target is only partially identifiable from the observed data. Our work lies at the interface of Bayesian statistics, deep learning, and deep generative modeling, with applications in genomics, microbiome research, and other high-throughput biological assays.

Our lab is highly collaborative and works across statistics, biology, medicine, and computer science. [Please contact us if you are interested in potential collaboration](mailto:JustinSilverman@psu.edu).

## longer form

Our group works on problems that are mathematically interesting, scientifically important, and often poorly served by standard modeling assumptions. We are especially interested in settings where the data are noisy, high-dimensional, biased, distribution-shifted, or fundamentally insufficient to identify the scientific quantity of interest without additional assumptions.

A central theme of our research is uncertainty quantification. We develop methods that not only make predictions, but also characterize what can and cannot be learned from the available data. This includes work on Bayesian inference, conformal prediction, post-hoc calibration, ensemble methods, and deep generative models whose uncertainty estimates remain meaningful under misspecification, measurement error, and dataset shift. More broadly, we are interested in bringing statistical rigor to modern machine learning, especially in scientific settings where overconfident black-box predictions can be misleading.

A second major theme is inference under partial identifiability. In many biomedical problems, important quantities cannot be recovered from the observed data alone without strong and often unverifiable assumptions. Our work develops methods that remain transparent about these limits while still supporting useful inference and decision-making. In practice, this includes problems involving compositional effects, unmeasured biological scale, measurement bias, unmeasured confounding, model misspecification, and imperfect proxy measurements.

Many of our applications arise in sequence count data, including microbiome and gene expression studies, where standard workflows often obscure the distinction between relative and absolute change. At the same time, we are increasingly interested in broader questions at the boundary of statistics and modern AI: how to build predictive models that know when they are uncertain, how to calibrate deep models after training, how to combine information across multiple views or modalities, and how to use deep generative models as principled statistical tools rather than merely flexible function approximators.

If a problem has elegant mathematics, meaningful uncertainty, and the potential for real scientific impact, there is a good chance we will be interested.

### example projects

+ Bayesian partially identified models for microbiome and gene expression studies, enabling more robust inference when biological scale is unobserved. [link](https://arxiv.org/abs/2201.03616)
+ Statistical methods for differential abundance and differential expression that explicitly address compositional bias and scale-dependent scientific targets.
+ Scalable Bayesian multinomial logistic-normal models for microbiome data analysis. [link](https://jmlr.org/papers/v23/19-882.html)
+ Bayesian conformal prediction, post-hoc calibration, and related methods for improving uncertainty estimates, prediction intervals, and conditional coverage.
+ Ensemble-based predictive methods that use disagreement between models to detect unreliable predictions, particularly under distribution shift.
+ Deep generative and probabilistic models for high-dimensional biological data, with an emphasis on calibration, robustness, and scientific interpretability.
+ Syndromic surveillance methods revealing substantial underestimation of COVID-19 prevalence in the United States. [link](https://www.science.org/doi/10.1126/scitranslmed.abc1126)
