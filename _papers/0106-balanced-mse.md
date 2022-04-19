---
layout: paper

title: "Balanced MSE for Imbalanced Visual Regression"
authors:
- Jiawei Ren
- Mingyuan Zhang
- Cunjun Yu
- Ziwei Liu

venue: "CVPR"
year: 2022

link: https://arxiv.org/abs/2203.16427

abstract: "
Data imbalance exists ubiquitously in real-world visual regressions, e.g., age
estimation and pose estimation, hurting the model's generalizability and
fairness. Thus, imbalanced regression gains increasing research attention
recently. Compared to imbalanced classification, imbalanced regression focuses
on continuous labels, which can be boundless and high-dimensional and hence
more challenging. In this work, we identify that the widely used Mean Square
Error (MSE) loss function can be ineffective in imbalanced regression. We
revisit MSE from a statistical view and propose a novel loss function, Balanced
MSE, to accommodate the imbalanced training label distribution. We further
design multiple implementations of Balanced MSE to tackle different real-world
scenarios, particularly including the one that requires no prior knowledge
about the training label distribution. Moreover, to the best of our knowledge,
Balanced MSE is the first general solution to high-dimensional imbalanced
regression. Extensive experiments on both synthetic and three real-world
benchmarks demonstrate the effectiveness of Balanced MSE.
"

who_suggested: George De Ath
status: suggested
---
[GitHub](https://github.com/jiawei-ren/BalancedMSE)
