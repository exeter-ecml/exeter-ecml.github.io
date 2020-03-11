---
layout: paper

title: "BOHB: Robust and Efficient Hyperparameter Optimization at Scale"

citation: "
Stefan Falkner, Aaron Klein, Frank Hutter,
BOHB: Robust and Efficient Hyperparameter Optimization at Scale
Proceedings of the 35th International Conference on Machine Learning, 
in PMLR 80:1437-1446, 2020
"

link: http://proceedings.mlr.press/v80/falkner18a.html

abstract: "
Modern deep learning methods are very sensitive to many hyperparameters, and, 
due to the long training times of state-of-the-art models, vanilla Bayesian 
hyperparameter optimization is typically computationally infeasible. On the 
other hand, bandit-based configuration evaluation approaches based on random 
search lack guidance and do not converge to the best configurations as 
quickly. Here, we propose to combine the benefits of both Bayesian optimization
and bandit-based methods, in order to achieve the best of both worlds: strong
anytime performance and fast convergence to optimal configurations. We propose
a new practical state-of-the-art hyperparameter optimization method, which
consistently outperforms both Bayesian optimization and Hyperband on a wide
range of problem types, including high-dimensional toy functions, support
vector machines, feed-forward neural networks, Bayesian neural networks, deep
reinforcement learning, and convolutional neural networks. Our method is robust
and versatile, while at the same time being conceptually simple and easy to
implement. 
"

who_suggested: George De Ath
---

More information: <https://www.automl.org/blog_bohb/>

Code: <https://github.com/automl/HpBandSter>
