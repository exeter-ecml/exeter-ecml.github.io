---
layout: paper

title: "High-Dimensional Bayesian Optimisation with Variational Autoencoders and Deep Metric Learning"
authors:
- Antoine Grosnit
- Rasul Tutunov
- Alexandre Max Maraval
- Ryan-Rhys Griffiths
- Alexander I. Cowen-Rivers
- Lin Yang,
- Lin Zhu
- Wenlong Lyu
- Zhitang Chen
- Jun Wang
- Jan Peters
- Haitham Bou-Ammar
venue: NeurIPS submission
year: 2021

link: https://arxiv.org/abs/2106.03609

abstract: "
We introduce a method based on deep metric learning to perform Bayesian
optimisation over high-dimensional, structured input spaces using variational 
autoencoders (VAEs). By extending ideas from supervised deep metric learning,
we address a longstanding problem in high-dimensional VAE Bayesian
optimisation, namely how to enforce a discriminative latent space as an
inductive bias. Importantly, we achieve such an inductive bias using just 1%
of the available labelled data relative to previous work, highlighting the
sample efficiency of our approach. As a theoretical contribution, we present
a proof of vanishing regret for our method. As an empirical contribution, we
present state-of-the-art results on real-world high-dimensional black-box
optimisation problems including property-guided molecule generation. It is
the hope that the results presented in this paper can act as a guiding
principle for realising effective high-dimensional Bayesian optimisation. 
"

who_suggested: George De Ath
status: suggested
---
- [github](https://github.com/huawei-noah/HEBO/tree/master/T-LBO)
