---
layout: paper

title: "Fair Bayesian Optimization"
authors:
- Valerio Perrone
- Michele Donini
- Krishnaram Kenthapadi
- Cédric Archambeau

venue: Proceedings of the 37th International Conference on Machine Learning
year: 2020

link: https://arxiv.org/abs/2006.05109

abstract: "
Given the increasing importance of machine learning (ML) in our lives, 
algorithmic fairness techniques have been proposed to mitigate biases that can
be amplified by ML. Commonly, these specialized techniques apply to a single
family of ML models and a specific definition of fairness, limiting their
effectiveness in practice. We introduce a general constrained Bayesian
optimization (BO) framework to optimize the performance of any ML model while
enforcing one or multiple fairness constraints. BO is a global optimization
method that has been successfully applied to automatically tune the 
hyperparameters of ML models. We apply BO with fairness constraints to a range
of popular models, including random forests, gradient boosting, and neural 
networks, showing that we can obtain accurate and fair solutions by acting 
solely on the hyperparameters. We also show empirically that our approach is 
competitive with specialized techniques that explicitly enforce fairness 
constraints during training, and outperforms preprocessing methods that learn
unbiased representations of the input data. Moreover, our method can be used in
synergy with such specialized fairness techniques to tune their 
hyperparameters. Finally, we study the relationship between hyperparameters and
fairness of the generated model. We observe a correlation between 
regularization and unbiased models, explaining why acting on the 
hyperparameters leads to ML models that generalize well and are fair. 
"

who_suggested: Fabrizio Costa

status: suggested
---
Author presentation: <https://slideslive.com/38930648/fair-bayesian-optimization><br/>
(We will watch this in the meeting)