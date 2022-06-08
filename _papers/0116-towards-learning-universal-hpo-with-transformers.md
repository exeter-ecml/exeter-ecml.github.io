---
layout: paper

title: "Towards Learning Universal Hyperparameter Optimizers with Transformers"
authors:
- Yutian Chen
- Xingyou Song
- Chansoo Lee
- Zi Wang
- Qiuyi Zhang
- David Dohan
- Kazuya Kawakami
- Greg Kochanski
- Arnaud Doucet
- Marc'aurelio Ranzato
- Sagi Perel
- Nando de Freitas

venue: "NeurIPS (submitted)"
year: 2022

link: https://arxiv.org/abs/2205.13320

abstract: "
Meta-learning hyperparameter optimization (HPO) algorithms from prior
experiments is a promising approach to improve optimization efficiency over
objective functions from a similar distribution. However, existing methods are
restricted to learning from experiments sharing the same set of
hyperparameters. In this paper, we introduce the OptFormer, the first
text-based Transformer HPO framework that provides a universal end-to-end
interface for jointly learning policy and function prediction when trained on
vast tuning data from the wild. Our extensive experiments demonstrate that the
OptFormer can imitate at least 7 different HPO algorithms, which can be
further improved via its function uncertainty estimates. Compared to a
Gaussian Process, the OptFormer also learns a robust prior distribution for
hyperparameter response functions, and can thereby provide more accurate and
better calibrated predictions. This work paves the path to future extensions
for training a Transformer-based model as a general HPO optimizer.
"

who_suggested: George De Ath
status: happened
---
