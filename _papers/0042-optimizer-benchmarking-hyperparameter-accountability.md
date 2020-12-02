---
layout: paper

title: "Optimizer Benchmarking Needs to Account for Hyperparameter Tuning"
authors:
- Prabhu Teja Sivaprasad
- Florian Mai
- Thijs Vogels
- Martin Jaggi
- François Fleuret

venue: International Conference on Machine Learning
year: 2020

link: https://proceedings.icml.cc/paper/2020/hash/0af787945872196b42c9f73ead2565c8-Abstract.html

abstract: "
The performance of optimizers, particularly in deep learning, depends
considerably on their chosen hyperparameter configuration. The efficacy of
optimizers is often studied under near-optimal problem-specific
hyperparameters, and finding these settings may be prohibitively costly for
practitioners. In this work, we argue that a fair assessment of optimizers'
performance must take the computational cost of hyperparameter tuning into
account, i.e., how easy it is to find good hyperparameter configurations using
an automatic hyperparameter search. Evaluating a variety of optimizers on an
extensive set of standard datasets and architectures, our results indicate
that Adam is the most practical solution, particularly in low-budget scenarios.
"

who_suggested: George De Ath

status: suggested
---
[Video presentation](https://www.idiap.ch/~prabhuteja/tunability.html)