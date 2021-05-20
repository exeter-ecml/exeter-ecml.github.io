---
layout: paper

title: "Bayesian Optimization with Approximate Set Kernels"
authors:
- Jungtaek Kim
- Michael McCourt
- Tackgeun You
- Saehoon Kim
- Seungjin Choi
venue: arXiv
year: 2020

link: https://arxiv.org/abs/1905.09780

abstract: "
We propose a practical Bayesian optimization method over sets, to minimize a
black-box function that takes a set as a single input. Because set inputs are
permutation-invariant, traditional Gaussian process-based Bayesian
optimization strategies which assume vector inputs can fall short. To address
this, we develop a Bayesian optimization method with *set kernel* that is used
to build surrogate functions. This kernel accumulates similarity over set
elements to enforce permutation-invariance, but this comes at a greater 
computational cost. To reduce this burden, we propose two key components: 
(i) a more efficient approximate set kernel which is still positive-definite
and is an unbiased estimator of the true set kernel with upper-bounded variance
in terms of the number of subsamples, (ii) a constrained acquisition function
optimization over sets, which uses symmetry of the feasible region that defines
a set input. Finally, we present several numerical experiments which
demonstrate that our method outperforms other methods. 
"

who_suggested: Tinkle Chugh

status: happened
---
[Code](https://github.com/jungtaekkim/bayeso)
