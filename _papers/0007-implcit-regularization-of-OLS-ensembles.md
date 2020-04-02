---
layout: paper

title: "The Implicit Regularization of Ordinary Least Squares Ensembles"

citation: "
D. LeJeune, H. Javadi, R. G. Baraniuk,
The Implicit Regularization of Ordinary Least Squares Ensembles,
to appear in The 23rd International Conference on Artificial Intelligence and Statistics (AISTATS),
2020
"

link: https://arxiv.org/abs/1910.04743

abstract: "
Ensemble methods that average over a collection of independent predictors that
are each limited to a subsampling of both the examples and features of the
training data command a significant presence in machine learning, such as the
ever-popular random forest, yet the nature of the subsampling effect,
particularly of the features, is not well understood. We study the case of an
ensemble of linear predictors, where each individual predictor is fit using
ordinary least squares on a random submatrix of the data matrix. We show that,
under standard Gaussianity assumptions, when the number of features selected
for each predictor is optimally tuned, the asymptotic risk of a large ensemble
is equal to the asymptotic ridge regression risk, which is known to be optimal
among linear predictors in this setting. In addition to eliciting this implicit
regularization that results from subsampling, we also connect this ensemble to
the dropout technique used in training deep (neural) networks, another strategy
that has been shown to have a ridge-like regularizing effect. 
"

who_suggested: George De Ath

status: suggested
---

To appear at AISTATS 2020.

Code: <https://github.com/dlej/ensemble-ols>
