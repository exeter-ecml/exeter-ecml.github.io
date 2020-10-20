---
layout: paper

title: "Bayesian Optimization by Density Ratio Estimation"
authors:
- Louis Tiao
- Aaron Klein
- Cedric Archambeau
- Edwin V. Bonilla
- Matthias Seeger
- Fabio Ramos

venue: Under review at ICLR
year: 2020

link: https://tiao.io/publication/bore-1/main.pdf

abstract: "
Bayesian optimization (BO) is among the most effective and widely-used blackbox
optimization methods. BO proposes solutions according to an explore-exploit
trade-off criterion encoded in an acquisition function, many of which are 
derived from the posterior predictive of a probabilistic surrogate model.
Prevalent among these is the expected improvement (EI). Naturally, the need to
ensure analytical tractability in the model poses limitations that can
ultimately hinder the efficiency and applicability of BO. In this paper, we
cast the computation of EI as a binary classification problem, building on the
well-known link between class probability estimation (CPE) and density ratio
estimation (DRE), and the lesser-known link between density ratios and EI. By
circumventing the tractability constraints imposed on the model, this
reformulation provides several natural advantages, not least in scalability,
increased flexibility, and greater representational capacity.
"

who_suggested: George De Ath

status: suggested
---
[Project website](https://tiao.io/publication/bore-1/)

[Supplementary material](https://tiao.io/publication/bore-1/supplementary.pdf)