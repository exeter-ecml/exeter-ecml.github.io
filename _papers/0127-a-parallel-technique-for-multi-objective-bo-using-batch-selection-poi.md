---
layout: paper

title: "A Parallel Technique for Multi-objective Bayesian Global Optimization: Using a Batch Selection of Probability of Improvement"
authors:
- Kaifeng Yang
- Guozhi Dong
- Michael Affenzeller

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2208.03685

abstract: "
Bayesian global optimization (BGO) is an efficient surrogate-assisted technique
for problems involving expensive evaluations. A parallel technique can be used
to parallelly evaluate the true-expensive objective functions in one iteration
to boost the execution time. An effective and straightforward approach is to
design an acquisition function that can evaluate the performance of a bath of
multiple solutions, instead of a single point/solution, in one iteration. This
paper proposes five alternatives of *Probability of Improvement* (PoI) with
multiple points in a batch (q-PoI) for multi-objective Bayesian global
optimization (MOBGO), taking the covariance among multiple points into account.
Both exact computational formulas and the Monte Carlo approximation algorithms
for all proposed q-PoIs are provided. Based on the distribution of the multiple
points relevant to the Pareto-front, the position-dependent behavior of the
five q-PoIs is investigated. Moreover, the five q-PoIs are compared with the
other nine state-of-the-art and recently proposed batch MOBGO algorithms on
twenty bio-objective benchmarks. The empirical experiments on different variety
of benchmarks are conducted to demonstrate the effectiveness of two greedy
q-PoIs (q-PoI-best and q-PoI-all) on low-dimensional problems and the
effectiveness of two explorative q-PoIs (q-PoI-one and q-PoI-worst) on
high-dimensional problems with difficult-to-approximate Pareto front
boundaries.
"

who_suggested: Tinkle Chugh
status: suggested
---
