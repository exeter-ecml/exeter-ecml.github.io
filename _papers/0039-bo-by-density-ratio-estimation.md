---
layout: paper

title: "BORE: Bayesian Optimization by Density-Ratio Estimation"
authors:
- Louis C. Tiao
- Aaron Klein
- Matthias W. Seeger
- Edwin V. Bonilla
- Cedric Archambeau
- Fabio Ramos

venue: International Conference on Machine Learning
year: 2021

link: http://proceedings.mlr.press/v139/tiao21a.html

abstract: "
Bayesian optimization (BO) is among the most effective and widely-used blackbox
optimization methods. BO proposes solutions according to an explore-exploit
trade-off criterion encoded in an acquisition function, many of which are
computed from the posterior predictive of a probabilistic surrogate model.
Prevalent among these is the expected improvement (EI). The need to ensure
analytical tractability of the predictive often poses limitations that can
hinder the efficiency and applicability of BO. In this paper, we cast the
computation of EI as a binary classification problem, building on the link
between class-probability estimation and density-ratio estimation, and the
lesser-known link between density-ratios and EI. By circumventing the
tractability constraints, this reformulation provides numerous advantages,
not least in terms of expressiveness, versatility, and scalability.
"

who_suggested: George De Ath

status: happened
---
- [Project website](https://tiao.io/publication/bore-2/)
- [github](https://github.com/ltiao/bore)
- [Presentation](https://slideslive.com/38942425/)
