---
layout: paper

title: "BOSH: Bayesian Optimization by Sampling Hierarchically"
authors:
- Henry B. Moss
- David S. Leslie
- Paul Rayson
venue: arXiv
year: 2020

link: https://arxiv.org/abs/2007.00939

abstract: "
Deployments of Bayesian Optimization (BO) for functions with stochastic
evaluations, such as parameter tuning via cross validation and simulation
optimization, typically optimize an average of a fixed set of noisy
realizations of the objective function. However, disregarding the true
objective function in this manner finds a high-precision optimum of the wrong
function. To solve this problem, we propose Bayesian Optimization by Sampling
Hierarchically (BOSH), a novel BO routine pairing a hierarchical Gaussian
process with an information-theoretic framework to generate a growing pool of
realizations as the optimization progresses. We demonstrate that BOSH provides
more efficient and higher-precision optimization than standard BO across
synthetic benchmarks, simulation optimization, reinforcement learning and
hyper-parameter tuning tasks."

who_suggested: Tinkle Chugh

status: suggested
---