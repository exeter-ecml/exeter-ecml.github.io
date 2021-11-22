---
layout: paper

title: "Laplace Redux -- Effortless Bayesian Deep Learning"
authors:
- Erik Daxberger
- Agustinus Kristiadi
- Alexander Immer
- Runa Eschenhagen
- Matthias Bauer
- Philipp Hennig
venue: NeurIPS
year: 2021

link: https://openreview.net/forum?id=gDcaUj4Myhn

abstract: "
Bayesian formulations of deep learning have been shown to have compelling
theoretical properties and offer practical functional benefits, such as
improved predictive uncertainty quantification and model selection. The Laplace
approximation (LA) is a classic, and arguably the simplest family of
approximations for the intractable posteriors of deep neural networks. Yet,
despite its simplicity, the LA is not as popular as alternatives like
variational Bayes or deep ensembles. This may be due to assumptions that the LA
is expensive due to the involved Hessian computation, that it is difficult to
implement, or that it yields inferior results. In this work we show that these
are misconceptions: we (i) review the range of variants of the LA including
versions with minimal cost overhead; (ii) introduce *laplace*, an easy-to-use
software library for PyTorch offering user-friendly access to all major flavors
of the LA; and (iii) demonstrate through extensive experiments that the LA is
competitive with more popular alternatives in terms of performance, while
excelling in terms of computational cost. We hope that this work will serve as
a catalyst to a wider adoption of the LA in practical deep learning, including
in domains where Bayesian approaches are not typically considered at the
moment.
"

who_suggested: George De Ath
status: happened
---
- [github](https://github.com/AlexImmer/Laplace)
- [11min presentation](https://www.youtube.com/watch?v=nMONiYLWWOU)
- [twitter posts](https://twitter.com/a1mmer/status/1454057888759037955)
- [blog](https://agustinus.kristia.de/techblog/2021/10/27/laplace/)
