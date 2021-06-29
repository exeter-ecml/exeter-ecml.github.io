---
layout: paper

title: "BOSH: Bayesian Optimization by Sampling Hierarchically"
authors:
- Henry B. Moss
- David S. Leslie
- Paul Rayson
venue: ICML Workshop on Real World Experiment Design and Active Learning
year: 2020

link: https://realworldml.github.io/files/cr/4_BOSH_ICML_Workshop_FINAL.pdf

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
- [PhD Thesis (Chapter 6.)](https://eprints.lancs.ac.uk/id/eprint/154461/1/2021mossphd.pdf)