---
layout: paper

title: "TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second"
authors:
- Noah Hollmann
- Samuel Müller
- Katharina Eggensperger
- Frank Hutter

venue: "arXiv"

year: 2022

link: https://arxiv.org/abs/2207.01848

abstract: "
We present TabPFN, a trained Transformer that can do supervised classification
for small tabular datasets in less than a second, needs no hyperparameter
tuning and is competitive with state-of-the-art classification methods. TabPFN
is fully entailed in the weights of our network, which accepts training and
test samples as a set-valued input and yields predictions for the entire test
set in a single forward pass. TabPFN is a Prior-Data Fitted Network (PFN) and
is trained offline once, to approximate Bayesian inference on synthetic
datasets drawn from our prior. This prior incorporates ideas from causal
reasoning: It entails a large space of structural causal models with a
preference for simple structures. On 30 datasets from the OpenML-CC18 suite, we
show that our method clearly outperforms boosted trees and performs on par with
complex state-of-the-art AutoML systems with up to 70× speedup. This increases
to a 3200× speedup when a GPU is available.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/automl/TabPFN)
- [Blog](https://www.automl.org/tabpfn-a-transformer-that-solves-small-tabular-classification-problems-in-a-second/)
