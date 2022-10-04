---
layout: paper

title: "Ensemble-based gradient inference for particle methods in optimization and sampling"
authors:
- Claudia Schillings
- Claudia Totzeck
- Philipp Wacker

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2209.15420

abstract: "
We propose an approach based on function evaluations and Bayesian inference to
extract higher-order differential information of objective functions from a
given ensemble of particles. Pointwise evaluation $$\\{V(x^i)\\}_i$$ of some
potential $$V$$ in an ensemble $$\\{x^i\\}_i$$ contains implicit information
about first or higher order derivatives, which can be made explicit with
little computational effort (ensemble-based gradient inference -- EGI). We
suggest to use this information for the improvement of established
ensemble-based numerical methods for optimization and sampling such as
Consensus-based optimization and Langevin-based samplers. Numerical studies
indicate that the augmented algorithms are often superior to their
gradient-free variants, in particular the augmented methods help the ensembles
to escape their initial domain, to explore multimodal, non-Gaussian settings
and to speed up the collapse at the end of optimization dynamics.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/MercuryBench/ensemble-based-gradient)
