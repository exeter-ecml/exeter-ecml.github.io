---
layout: paper

title: "Invariance Learning in Deep Neural Networks with Differentiable Laplace Approximations"

authors:
- Alexander Immer
- Tycho F.A. van der Ouderaa
- Gunnar Rätsch
- Vincent Fortuin
- Mark van der Wilk

venue: "NeurIPS"

year: 2022

link: https://arxiv.org/abs/2202.10638

abstract: "
Data augmentation is commonly applied to improve performance of deep learning
by enforcing the knowledge that certain transformations on the input preserve
the output. Currently, the data augmentation parameters are chosen by human
effort and costly cross-validation, which makes it cumbersome to apply to new
datasets. We develop a convenient gradient-based method for selecting the data
augmentation without validation data during training of a deep neural network.
Our approach relies on phrasing data augmentation as an invariance in the prior
distribution on the functions of a neural network, which allows us to learn it
using Bayesian model selection. This has been shown to work in Gaussian
processes, but not yet for deep neural networks. We propose a differentiable
Kronecker-factored Laplace approximation to the marginal likelihood as our
objective, which can be optimised without human supervision or validation data.
We show that our method can successfully recover invariances present in the
data, and that this improves generalisation and data efficiency on image
datasets.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/tychovdo/lila)
- [Twitter thread](https://twitter.com/tychovdo/status/1580955370813788163)
