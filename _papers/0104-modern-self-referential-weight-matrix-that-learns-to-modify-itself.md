---
layout: paper

title: "A Modern Self-Referential Weight Matrix That Learns to Modify Itself"
authors:
- Kazuki Irie
- Imanol Schlag
- Róbert Csordás
- Jürgen Schmidhuber

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2202.05780

abstract: "
The weight matrix (WM) of a neural network (NN) is its program. The programs
of many traditional NNs are learned through gradient descent in some error
function, then remain fixed. The WM of a self-referential NN, however, can keep
rapidly modifying all of itself during runtime. In principle, such NNs can
meta-learn to learn, and meta-meta-learn to meta-learn to learn, and so on, in
the sense of recursive self-improvement. While NN architectures potentially
capable of implementing such behavior have been proposed since the '90s, there
have been few if any practical studies. Here we revisit such NNs, building upon
recent successes of fast weight programmers and closely related linear
Transformers. We propose a scalable self-referential WM (SRWM) that uses outer
products and the delta update rule to modify itself. We evaluate our SRWM in
supervised few-shot learning and in multi-task reinforcement learning with
procedurally generated game environments. Our experiments demonstrate both
practical applicability and competitive performance of the proposed SRWM.
"

who_suggested: George De Ath
status: suggested
---
- [NeurIPS 2021 Workshop paper](https://openreview.net/forum?id=lVUGfLpNpCF)
