---
layout: paper

title: "A Very Simple Safe-Bayesian Random Forest"
authors:
- Novi Quadrianto
- Zoubin Ghahramani,

venue: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2015

link: https://ieeexplore.ieee.org/document/6920043

abstract: "
Random forests works by averaging several predictions of de-correlated trees.
We show a conceptually radical approach to generate a random forest: random
sampling of many trees from a prior distribution, and subsequently performing a
weighted ensemble of predictive probabilities. Our approach uses priors that 
allow sampling of decision trees even before looking at the data, and a power
likelihood that explores the space spanned by combination of decision trees. 
While each tree performs Bayesian inference to compute its predictions, our 
aggregation procedure uses the power likelihood rather than the likelihood and
is therefore strictly speaking not Bayesian. Nonetheless, we refer to it as a
Bayesian random forest but with a built-in safety. The safeness comes as it
has good predictive performance even if the underlying probabilistic model is
wrong. We demonstrate empirically that our Safe-Bayesian random forest
outperforms MCMC or SMC based Bayesian decision trees in term of speed and
accuracy, and achieves competitive performance to entropy or Gini optimised
random forest, yet is very simple to construct.
"

who_suggested: Richard Everson

status: happened
---
If you can't access the paper at the link above,
you can also get it from [Sussex University](http://sro.sussex.ac.uk/id/eprint/54606/1/QuaGha14.pdf).