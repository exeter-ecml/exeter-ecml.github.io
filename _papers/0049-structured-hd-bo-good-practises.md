---
layout: paper

title: "Good practices for Bayesian Optimization of high dimensional structured spaces"
authors:
- Eero Siivola
- Javier Gonzalez
- Andrei Paleyes
- Aki Vehtari
venue: arXiv
year: 2020

link: https://arxiv.org/abs/2012.15471

abstract: "
The increasing availability of structured but high dimensional data has opened
new opportunities for optimization. One emerging and promising avenue is the
exploration of unsupervised methods for projecting structured high dimensional
data into low dimensional continuous representations, simplifying the
optimization problem and enabling the application of traditional optimization
methods. However, this line of research has been purely methodological with
little connection to the needs of practitioners so far. In this paper, we study
the effect of different search space design choices for performing Bayesian
Optimization in high dimensional structured datasets. In particular, we analyse
the influence of the dimensionality of the latent space, the role of the
acquisition function and evaluate new methods to automatically define the
optimization bounds in the latent space. Finally, based on experimental results
using synthetic and real datasets, we provide recommendations for the
practitioners.
"

who_suggested: George De Ath

status: suggested
---
[Code](https://github.com/esiivola/hdssbo)
