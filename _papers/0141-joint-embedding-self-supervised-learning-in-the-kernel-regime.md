---
layout: paper

title: "Joint Embedding Self-Supervised Learning in the Kernel Regime"
authors:
- Bobak T. Kiani
- Randall Balestriero
- Yubei Chen
- Seth Lloyd
- Yann LeCun

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2209.14884

abstract: "
The fundamental goal of self-supervised learning (SSL) is to produce useful
representations of data without access to any labels for classifying the data.
Modern methods in SSL, which form representations based on known or
constructed relationships between samples, have been particularly effective at
this task. Here, we aim to extend this framework to incorporate algorithms
based on kernel methods where embeddings are constructed by linear maps acting
on the feature space of a kernel. In this kernel regime, we derive methods to
find the optimal form of the output representations for contrastive and
non-contrastive loss functions. This procedure produces a new representation
space with an inner product denoted as the induced kernel which generally
correlates points which are related by an augmentation in kernel space and
de-correlates points otherwise. We analyze our kernel model on small datasets
to identify common features of self-supervised learning algorithms and gain
theoretical insights into their performance on downstream tasks.
"

who_suggested: George De Ath
status: suggested
---
- See also: <https://arxiv.org/abs/2108.13097>
