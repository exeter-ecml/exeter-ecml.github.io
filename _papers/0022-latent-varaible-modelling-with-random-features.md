---
layout: paper

title: "Latent variable modeling with random features"
authors:
- Gregory Gundersen
- Michael Minyi Zhang
- Barbara Engelhardt
venue: arXiv
year: 2020

link: https://arxiv.org/abs/2006.11145

abstract: "
Gaussian process-based latent variable models are flexible and theoretically
grounded tools for nonlinear dimension reduction, but generalizing to
non-Gaussian data likelihoods within this nonlinear framework is statistically
challenging. Here, we use random features to develop a family of nonlinear
dimension reduction models that are easily extensible to non-Gaussian data
likelihoods; we call these random feature latent variable models (RFLVMs).
By approximating a nonlinear relationship between the latent space and the
observations with a function that is linear with respect to random features,
we induce closed-form gradients of the posterior distribution with respect to
the latent variable. This allows the RFLVM framework to support computationally
tractable nonlinear latent variable models for a variety of data likelihoods in
the exponential family without specialized derivations. Our generalized RFLVMs
produce results comparable with other state-of-the-art dimension reduction
methods on diverse types of data, including neural spike train recordings,
images, and text data.
"

who_suggested: George De Ath

status: suggested
---
