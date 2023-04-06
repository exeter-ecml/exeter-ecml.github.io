---
layout: paper

title: "Self-Distillation for Gaussian Process Regression and Classification"

authors:
- Kenneth Borup
- Lars Nørvang Andersen

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2304.02641

abstract: "
We propose two approaches to extend the notion of knowledge distillation to
Gaussian Process Regression (GPR) and Gaussian Process Classification (GPC);
data-centric and distribution-centric. The data-centric approach resembles
most current distillation techniques for machine learning, and refits a model
on deterministic predictions from the teacher, while the distribution-centric
approach, re-uses the full probabilistic posterior for the next iteration. By
analyzing the properties of these approaches, we show that the data-centric
approach for GPR closely relates to known results for self-distillation of
kernel ridge regression and that the distribution-centric approach for GPR
corresponds to ordinary GPR with a very particular choice of hyperparameters.
Furthermore, we demonstrate that the distribution-centric approach for GPC
approximately corresponds to data duplication and a particular scaling of the
covariance and that the data-centric approach for GPC requires redefining the
model from a Binomial likelihood to a continuous Bernoulli likelihood to be
well-specified. To the best of our knowledge, our proposed approaches are the
first to formulate knowledge distillation specifically for Gaussian Process
models.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/Kennethborup/gaussian_process_self_distillation)
- [arXiv paper](https://arxiv.org/abs/2303.09489)
