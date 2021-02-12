---
layout: paper

title: "Liberty or Depth: Deep Bayesian Neural Nets Do Not Need Complex Weight Posterior Approximations"
authors:
- Sebastian Farquhar
- Lewis Smith
- Yarin Gal

venue: Advances In Neural Information Processing Systems.
year: 2020

link: https://papers.nips.cc/paper/2020/hash/2dfe1946b3003933b7f8ddd71f24dbb1-Abstract.html

abstract: "
We challenge the longstanding assumption that the mean-field approximation for
variational inference in Bayesian neural networks is severely restrictive, and
show this is not the case in deep networks. We prove several results indicating
that deep mean-field variational weight posteriors can induce similar
distributions in function-space to those induced by shallower networks with
complex weight posteriors. We validate our theoretical contributions
empirically, both through examination of the weight posterior using Hamiltonian
Monte Carlo in small models and by comparing diagonal- to structured-covariance
in large settings. Since complex variational posteriors are often expensive and
cumbersome to implement, our results suggest that using mean-field variational
inference in a deeper model is both a practical and theoretically justified
alternative to structured approximations.
"

who_suggested: George De Ath

status: suggested
---
[Blog post](https://oatml.cs.ox.ac.uk/blog/2020/11/29/liberty_or_depth.html)

[Twitter thread](https://twitter.com/seb_far/status/1333821891933589505)

[40min presentation](https://www.youtube.com/watch?v=p2vOZg1xoE0)
