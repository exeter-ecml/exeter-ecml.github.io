---
layout: paper

title: "Scalable Thompson Sampling using Sparse Gaussian Process Models"
authors:
- Sattar Vakili
- Henry Moss
- Artem Artemev
- Vincent Dutordoir
- Victor Picheny

venue: "NeurIPS"
year: 2021

link: https://papers.nips.cc/paper/2021/hash/2c7f9ccb5a39073e24babc3a4cb45e60-Abstract.html

abstract: "
Thompson Sampling (TS) from Gaussian Process (GP) models is a powerful tool
for the optimization of black-box functions. Although TS enjoys strong
theoretical guarantees and convincing empirical performance, it incurs a large
computational overhead that scales polynomially with the optimization budget.
Recently, scalable TS methods based on sparse GP models have been proposed to
increase the scope of TS, enabling its application to problems that are
sufficiently multi-modal, noisy or combinatorial to require more than a few
hundred evaluations to be solved. However, the approximation error introduced
by sparse GPs invalidates all existing regret bounds. In this work, we perform
a theoretical and empirical analysis of scalable TS. We provide theoretical
guarantees and show that the drastic reduction in computational complexity of
scalable TS can be enjoyed without loss in the regret performance over the
standard TS. These conceptual claims are validated for practical
implementations of scalable TS on synthetic benchmarks and as part of a
real-world high-throughput molecular design task.
"

who_suggested: Tinkle Chugh
status: happened
---
- [NeurIPS talk (14min)](https://papertalk.org/papertalks/36808)
