---
layout: paper

title: "A Learning-based Innovized Progress Operator for Faster Convergence in Evolutionary Multi-objective Optimization"
authors:
- Sukrit Mittal
- Dhish Kumar Saxena
- Kalyanmoy Deb
- Erik D. Goodman

venue: "ACM TELO"
year: 2022

link: https://dl.acm.org/doi/full/10.1145/3474059

abstract: "
Learning effective problem information from already explored search space in
an optimization run, and utilizing it to improve the convergence of subsequent
solutions, have represented important directions in Evolutionary
Multi-objective Optimization (EMO) research. In this article, a machine
learning (ML)-assisted approach is proposed that: (a) maps the solutions from
earlier generations of an EMO run to the current non-dominated solutions in
the decision space; (b) learns the salient patterns in the mapping using an ML
method, here an artificial neural network (ANN); and (c) uses the learned ML
model to advance some of the subsequent offspring solutions in an adaptive
manner. Such a multi-pronged approach, quite different from the popular
surrogate-modeling methods, leads to what is here referred to as the Innovized
Progress (IP) operator. On several test and engineering problems involving two
and three objectives, with and without constraints, it is shown that an EMO
algorithm assisted by the IP operator offers faster convergence behavior,
compared to its base version independent of the IP operator. The results are
encouraging, pave a new path for the performance improvement of EMO
algorithms, and set the motivation for further exploration on more challenging
problems.
"

who_suggested: George De Ath
status: suggested
---
