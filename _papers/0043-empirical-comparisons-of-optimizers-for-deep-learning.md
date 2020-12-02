---
layout: paper

title: "On Empirical Comparisons of Optimizers for Deep Learning"
authors:
- Dami Choi
- Christopher Shallue
- Zachary Nado
- Jaehoon Lee
- Chris J. Maddison
- George E. Dahl

venue: arXiv
year: 2020

link: https://arxiv.org/abs/1910.05446

abstract: "
Selecting an optimizer is a central step in the contemporary deep learning
pipeline. In this paper, we demonstrate the sensitivity of optimizer
comparisons to the hyperparameter tuning protocol. Our findings suggest that
the hyperparameter search space may be the single most important factor
explaining the rankings obtained by recent empirical comparisons in the
literature. In fact, we show that these results can be contradicted when
hyperparameter search spaces are changed. As tuning effort grows without bound,
more general optimizers should never underperform the ones they can approximate
(i.e., Adam should never perform worse than momentum), but recent attempts to
compare optimizers either assume these inclusion relationships are not
practically relevant or restrict the hyperparameters in ways that break the
inclusions. In our experiments, we find that inclusion relationships between
optimizers matter in practice and always predict optimizer comparisons. In 
particular, we find that the popular adaptive gradient methods never
underperform momentum or gradient descent. We also report practical tips around
tuning often ignored hyperparameters of adaptive gradient methods and raise
concerns about fairly benchmarking optimizers for neural network training. 
"

who_suggested: George De Ath

status: suggested
---
