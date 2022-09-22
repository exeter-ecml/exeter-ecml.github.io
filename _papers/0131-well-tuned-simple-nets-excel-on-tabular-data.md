---
layout: paper

title: "Well-tuned Simple Nets Excel on Tabular Datasets"
authors:
- Arlind Kadra
- Marius Lindauer
- Frank Hutter
- Josif Grabocka

venue: "NeurIPS"
year: 2021

link: https://proceedings.neurips.cc/paper/2021/hash/c902b497eb972281fb5b4e206db38ee6-Abstract.html

abstract: "
Tabular datasets are the last *unconquered castle* for deep learning, with
traditional ML methods like Gradient-Boosted Decision Trees still performing
strongly even against recent specialized neural architectures. In this paper,
we hypothesize that the key to boosting the performance of neural networks lies
in rethinking the joint and simultaneous application of a large set of modern
regularization techniques. As a result, we propose regularizing plain
Multilayer Perceptron (MLP) networks by searching for the optimal
combination/cocktail of 13 regularization techniques for each dataset using a
joint optimization over the decision on which regularizers to apply and their
subsidiary hyperparameters. We empirically assess the impact of these
regularization cocktails for MLPs in a large-scale empirical study comprising
40 tabular datasets and demonstrate that (i) well-regularized plain MLPs
significantly outperform recent state-of-the-art specialized neural network
architectures, and (ii) they even outperform strong traditional ML methods,
such as XGBoost.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/releaunifreiburg/WellTunedSimpleNets)
