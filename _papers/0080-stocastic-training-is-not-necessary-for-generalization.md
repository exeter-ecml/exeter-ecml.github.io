---
layout: paper

title: "Stochastic Training is Not Necessary for Generalization"
authors:
- Jonas Geiping
- Micah Goldblum
- Phillip E. Pope
- Michael Moeller
- Tom Goldstein
venue: arXiv
year: 2021

link: https://arxiv.org/abs/2109.14119

abstract: "
It is widely believed that the implicit regularization of stochastic gradient
descent (SGD) is fundamental to the impressive generalization behavior we
observe in neural networks. In this work, we demonstrate that non-stochastic
full-batch training can achieve strong performance on CIFAR-10 that is on-par
with SGD, using modern architectures in settings with and without data
augmentation. To this end, we utilize modified hyperparameters and show that
the implicit regularization of SGD can be completely replaced with explicit
regularization. This strongly suggests that theories that rely heavily on
properties of stochastic sampling to explain generalization are incomplete, as
strong generalization behavior is still observed in the absence of stochastic
sampling. Fundamentally, deep learning can succeed without stochasticity. Our
observations further indicate that the perceived difficulty of full-batch
training is largely the result of its optimization properties and the
disproportionate time and effort spent by the ML community tuning optimizers
and hyperparameters for small-batch training. 
"

who_suggested: George De Ath
status: suggested
---
- [github](http://github.com/JonasGeiping/fullbatchtraining)
- [reddit thread](https://www.reddit.com/r/MachineLearning/comments/pziubx/r_stochastic_training_is_not_necessary_for/)