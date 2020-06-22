---
layout: paper

title: "Uncertainty quantification using martingales for misspecified Gaussian processes"
authors:
- Willie Neiswanger
- Aaditya Ramdas
venue: arXiv
year: 2020

link: https://arxiv.org/abs/2006.07368

abstract: "
We address uncertainty quantification for Gaussian processes (GPs) under 
misspecified priors, with an eye towards Bayesian Optimization (BO). GPs are
widely used in BO because they easily enable exploration based on posterior
uncertainty bands. However, this convenience comes at the cost of robustness:
a typical function encountered in practice is unlikely to have been drawn from
the data scientist's prior, in which case uncertainty estimates can be
misleading, and the resulting exploration can be suboptimal. This brittle
behavior is convincingly demonstrated in simple simulations. We present a
frequentist approach to GP/BO uncertainty quantification. We utilize the GP
framework as a working model, but do not assume correctness of the prior. We
instead construct a confidence sequence (CS) for the unknown function using
martingale techniques. There is a necessary cost to achieving robustness: if
the prior was correct, posterior GP bands are narrower than our CS. 
Nevertheless, when the prior is wrong, our CS is statistically valid and
empirically outperforms standard GP methods, in terms of both coverage and
utility for BO. Additionally, we demonstrate that powered likelihoods provide
robustness against model misspecification. 
"

who_suggested: George De Ath

status: suggested
---
