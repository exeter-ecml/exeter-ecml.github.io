---
layout: paper

title: "Why do tree-based models still outperform deep learning on tabular data?"
authors:
- Leo Grinsztajn
- Edouard Oyallon
- Gael Varoquaux

venue: "NeurIPS"
year: 2022

link: https://openreview.net/forum?id=Fp7__phQszn

abstract: "
While deep learning has enabled tremendous progress on text and image datasets,
its superiority on tabular data is not clear. We contribute extensive
benchmarks of standard and novel deep learning methods as well as tree-based
models such as XGBoost and Random Forests, across a large number of datasets
and hyperparameter combinations. We define a standard set of 45 datasets from
varied domains with clear characteristics of tabular data and a benchmarking
methodology accounting for both fitting models and finding good
hyperparameters. Results show that tree-based models remain state-of-the-art on
medium-sized data (10K samples) even without accounting for their superior
speed. To understand this gap, we conduct an empirical investigation into the
differing inductive biases of tree-based models and neural networks. This leads
to a series of challenges which should guide researchers aiming to build
tabular-specific neural networks: 1) be robust to uninformative features, 2)
preserve the orientation of the data, and 3) be able to easily learn irregular
functions. To stimulate research on tabular architectures, we contribute a
standard benchmark and every point of a 20,000 compute hours hyperparameter
search for each learner.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/LeoGrin/tabular-benchmark)
