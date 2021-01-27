---
layout: paper

title: "Expressive yet Tractable Bayesian Deep Learning via Subnetwork Inference"
authors:
- Erik Daxberger
- Eric Nalisnick
- James Urquhart Allingham
- Javier Antoran
- José Miguel Hernández-Lobato
venue: Advances in Approximate Bayesian Inference
year: 2021

link: https://openreview.net/forum?id=WqMlMsZ07A

abstract: "
Scaling Bayesian inference to the large parameter spaces of deep neural
networks requires restrictive approximations. We propose performing inference
over only a small subset of the model parameters while keeping all others as
point estimates. This enables us to use expressive posterior approximations
that are intractable in the full model. In particular, we develop a practical
and scalable Bayesian deep learning method that first trains a point estimate,
and then infers a full covariance Gaussian posterior approximation over a
subnetwork. We propose a subnetwork selection procedure which aims to
optimally preserve posterior uncertainty. Empirical studies demonstrate the
effectiveness of our approach.
"

who_suggested: George De Ath

status: suggested
---
[Video presentation](https://www.youtube.com/watch?v=HqyhSK_2bHA)

[Old (rejected) ICLR 2021 submission reviews](https://openreview.net/forum?id=C4-QQ1EHNcI)
