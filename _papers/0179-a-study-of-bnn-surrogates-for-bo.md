---
layout: paper

title: "A Study of Bayesian Neural Network Surrogates for Bayesian Optimization"

authors:
- Yucen Lily Li
- Tim G. J. Rudner
- Andrew Gordon Wilson

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2305.20028

abstract: "
Bayesian optimization is a highly efficient approach to optimizing objective
functions which are expensive to query. These objectives are typically
represented by Gaussian process (GP) surrogate models which are easy to
optimize and support exact inference. While standard GP surrogates have been
well-established in Bayesian optimization, Bayesian neural networks (BNNs) have
recently become practical function approximators, with many benefits over
standard GPs such as the ability to naturally handle non-stationarity and learn
representations for high-dimensional data. In this paper, we study BNNs as
alternatives to standard GP surrogates for optimization. We consider a variety
of approximate inference procedures for finite-width BNNs, including
high-quality Hamiltonian Monte Carlo, low-cost stochastic MCMC, and heuristics
such as deep ensembles. We also consider infinite-width BNNs and partially
stochastic models such as deep kernel learning. We evaluate this collection of
surrogate models on diverse problems with varying dimensionality, number of
objectives, non-stationarity, and discrete and continuous inputs. We find: (i)
the ranking of methods is highly problem dependent, suggesting the need for
tailored inductive biases; (ii) HMC is the most successful approximate
inference procedure for fully stochastic BNNs; (iii) full stochasticity may be
unnecessary as deep kernel learning is relatively competitive; (iv)
infinite-width BNNs are particularly promising, especially in high dimensions.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/yucenli/bnn-bo)
- [Twitter thread (AGW)](https://twitter.com/andrewgwils/status/1664077925388279810)
