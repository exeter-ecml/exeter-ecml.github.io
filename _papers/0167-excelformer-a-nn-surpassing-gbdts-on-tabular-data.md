---
layout: paper

title: "ExcelFormer: A Neural Network Surpassing GBDTs on Tabular Data"

authors:
- Jintai Chen
- Jiahuan Yan
- Danny Ziyi Chen
- Jian Wu

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2301.02819

abstract: "
Though neural networks have achieved enormous breakthroughs on various fields
(e.g., computer vision) in supervised learning, they still trailed the
performances of GBDTs on tabular data thus far. Delving into this issue, we
identify that a proper handling of feature interactions and feature embedding
is crucial to the success of neural networks on tabular data. We develop a
novel neural network called ExcelFormer, which alternates in turn two attention
modules that respectively manipulate careful feature interactions and feature
embedding updates. A bespoke training methodology is jointly introduced to
facilitate the model performances. By initializing parameters with minuscule
values, these attention modules are attenuated when the training begins, and
the effects of feature interactions and embedding updates progressively grow up
to optimum levels under the guidance of the proposed specific regularization
approaches Swap-Mix and Hidden-Mix as the training proceeds. Experiments on 25
public tabular datasets show that our ExcelFormer is superior to
extremely-tuned GBDTs, which is an unprecedented achievement of neural networks
in supervised tabular learning.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/WhatAShot/ExcelFormer)
