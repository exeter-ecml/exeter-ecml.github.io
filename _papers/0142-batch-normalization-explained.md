---
layout: paper

title: "Batch Normalization Explained"
authors:
- Randall Balestriero
- Richard G. Baraniuk
venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2209.14778

abstract: "
A critically important, ubiquitous, and yet poorly understood ingredient in
modern deep networks (DNs) is batch normalization (BN), which centers and
normalizes the feature maps. To date, only limited progress has been made
understanding why BN boosts DN learning and inference performance; work has
focused exclusively on showing that BN smooths a DN's loss landscape. In this
paper, we study BN theoretically from the perspective of function
approximation; we exploit the fact that most of today's state-of-the-art DNs
are continuous piecewise affine (CPA) splines that fit a predictor to the
training data via affine mappings defined over a partition of the input space
(the so-called 'linear regions'). *We demonstrate that BN is an
unsupervised learning technique that -- independent of the DN's weights or
gradient-based learning -- adapts the geometry of a DN's spline partition to
match the data.* BN provides a 'smart initialization' that boosts the
performance of DN learning, because it adapts even a DN initialized with
random weights to align its spline partition with the data. We also show that
the variation of BN statistics between mini-batches introduces a dropout-like
random perturbation to the partition boundaries and hence the decision
boundary for classification problems. This per mini-batch perturbation reduces
overfitting and improves generalization by increasing the margin between the
training samples and the decision boundary.
"

who_suggested: George De Ath
status: suggested
---
- [Twitter thread](https://twitter.com/randall_balestr/status/1575842431819743233)
