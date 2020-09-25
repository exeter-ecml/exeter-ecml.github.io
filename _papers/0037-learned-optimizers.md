---
layout: paper

title: "Tasks, stability, architecture, and compute: Training more effective learned optimizers, and using them to train themselves"
authors:
- Luke Metz
- Niru Maheswaranathan
- C. Daniel Freeman
- Ben Poole
- Jascha Sohl-Dickstein

venue: arXiv
year: 2020

link: https://arxiv.org/abs/2009.11243

abstract: "
Much as replacing hand-designed features with learned functions has 
revolutionized how we solve perceptual tasks, we believe learned algorithms
will transform how we train models. In this work we focus on general-purpose
learned optimizers capable of training a wide variety of problems with no 
user-specified hyperparameters. We introduce a new, neural network 
parameterized, hierarchical optimizer with access to additional features such
as validation loss to enable automatic regularization. Most learned optimizers
have been trained on only a single task, or a small number of tasks. We train
our optimizers on thousands of tasks, making use of orders of magnitude more
compute, resulting in optimizers that generalize better to unseen tasks. The
learned optimizers not only perform well, but learn behaviors that are distinct
from existing first order optimizers. For instance, they generate update steps
that have implicit regularization and adapt as the problem hyperparameters 
(e.g. batch size) or architecture (e.g. neural network width) change. Finally,
these learned optimizers show evidence of being useful for out of distribution
tasks such as training themselves from scratch.
"

who_suggested: George De Ath

status: suggested
---
Twitter threads talking about the work: 
[#1](https://twitter.com/Luke_Metz/status/1308951548979011585)
[#2](https://twitter.com/jaschasd/status/1308966305525952514)

TaskSet dataset:
[paper](https://arxiv.org/abs/2002.11887)
[code](https://github.com/google-research/google-research/tree/master/task_set)
