---
layout: paper

title: "Bayesian Optimization with Conformal Coverage Guarantees"

authors:
- Samuel Stanton
- Wesley Maddox
- Andrew Gordon Wilson

venue: "NeurIPS"

year: 2022

link: https://arxiv.org/abs/2210.12496

abstract: "
Bayesian optimization is a coherent, ubiquitous approach to decision-making
under uncertainty, with applications including multi-arm bandits, active
learning, and black-box optimization. Bayesian optimization selects decisions
(i.e. objective function queries) with maximal expected utility with respect to
the posterior distribution of a Bayesian model, which quantifies reducible,
epistemic uncertainty about query outcomes. In practice, subjectively
implausible outcomes can occur regularly for two reasons: 1) model
misspecification and 2) covariate shift. Conformal prediction is an uncertainty
quantification method with coverage guarantees even for misspecified models and
a simple mechanism to correct for covariate shift. We propose conformal
Bayesian optimization, which directs queries towards regions of search space
where the model predictions have guaranteed validity, and investigate its
behavior on a suite of black-box optimization tasks and tabular ranking tasks.
In many cases we find that query coverage can be significantly improved without
harming sample-efficiency.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/samuelstanton/conformal-bayesopt)
