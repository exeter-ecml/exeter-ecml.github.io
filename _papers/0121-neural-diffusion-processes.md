---
layout: paper

title: "Neural Diffusion Processes"
authors:
- Vincent Dutordoir
- Alan Saul
- Zoubin Ghahramani
- Fergus Simpson

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2206.10550

abstract: "
Gaussian processes provide an elegant framework for specifying prior and
posterior distributions over functions. They are, however, also
computationally expensive, and limited by the expressivity of their covariance
function. We propose Neural Diffusion Processes (NDPs), a novel approach based
upon diffusion models, that learn to sample from distributions over functions.
Using a novel attention block, we can incorporate properties of stochastic
processes, such as exchangeability, directly into the NDP's architecture. We
empirically show that NDPs are able to capture functional distributions that
are close to the true Bayesian posterior of a Gaussian process. This enables a
variety of downstream tasks, including hyperparameter marginalisation and
Bayesian optimisation.
"

who_suggested: George De Ath
status: suggested
---
- [twitter thread](https://twitter.com/vdutor/status/1534875063245328384)
