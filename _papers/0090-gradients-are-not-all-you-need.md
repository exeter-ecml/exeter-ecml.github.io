---
layout: paper

title: "Gradients are Not All You Need"
authors:
- Luke Metz
- C. Daniel Freeman
- Samuel S. Schoenholz
- Tal Kachman
venue: arXiv
year: 2021

link: https://arxiv.org/abs/2111.05803

abstract: "
Differentiable programming techniques are widely used in the community and are
responsible for the machine learning renaissance of the past several decades.
While these methods are powerful, they have limits. In this short report, we
discuss a common chaos based failure mode which appears in a variety of
differentiable circumstances, ranging from recurrent neural networks and
numerical physics simulation to training learned optimizers. We trace this
failure to the spectrum of the Jacobian of the system under study, and provide
criteria for when a practitioner might expect this failure to spoil their
differentiation based optimization algorithms.
"

who_suggested: George De Ath
status: suggested
---
- [summary twitter thread](https://twitter.com/Luke_Metz/status/1458661090326286336)
