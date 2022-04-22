---
layout: paper

title: "GParareal: A time-parallel ODE solver using Gaussian process emulation"
authors:
- Kamran Pentland
- Massimiliano Tamborrino
- T. J. Sullivan
- James Buchanan
- L. C. Appel

venue: "British Applied Mathematics Colloquium"
year: 2022

link: https://arxiv.org/abs/2201.13418

abstract: "
Sequential numerical methods for integrating initial value problems (IVPs) can
be prohibitively expensive when high numerical accuracy is required over the
entire interval of integration. One remedy is to integrate in a parallel
fashion, *predicting* the solution serially using a cheap (coarse) solver and
*correcting* these values using an expensive (fine) solver that runs in
parallel on a number of temporal subintervals. In this work, we propose a
time-parallel algorithm (GParareal) that solves IVPs by modelling the
correction term, i.e. the difference between fine and coarse solutions, using
a Gaussian process emulator. This approach compares favourably with the
classic parareal algorithm and we demonstrate, on a number of IVPs, that
GParareal can converge in fewer iterations than parareal, leading to an
increase in parallel speed-up. GParareal also manages to locate solutions to
certain IVPs where parareal fails and has the additional advantage of being
able to use archives of legacy solutions, e.g. solutions from prior runs of
the IVP for different initial conditions, to further accelerate convergence of
the method - something that existing time-parallel methods do not do.
"

who_suggested: Andy Corbett
status: suggested
---
[GitHub](https://github.com/kpentland/GParareal)
