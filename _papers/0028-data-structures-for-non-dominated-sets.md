---
layout: paper

title: "Data structures for non-dominated sets: implementations and empirical assessment of two decades of advances"
authors:
- Jonathan Fieldsend

venue: Proceedings of the 2020 Genetic and Evolutionary Computation Conference
year: 2020

link: https://dl.acm.org/doi/abs/10.1145/3377930.3390150

abstract: "
Many data structures have been developed over the last two decades for the
storage and efficient update of unconstrained sets of mutually non-dominating
solutions. Typically, analysis has been provided in the original works for
these data structures in terms of worst/average case complexity performance.
Often, however, other aspects such as rebalancing costs of underlying data
structures, cache sizes, etc., can also significantly affect behaviour.
Empirical performance comparison has often (but not always) been limited to
run-time comparison with a basic linear list. No comprehensive comparison
between the different specialised data structures proposed in the last two
decades has thus far been undertaken. We take significant strides in addressing
this here. Eight data structures from the literature are implemented within the
same overarching open source Java framework. We additionally highlight and
rectify some errors in published work --- and offer additional efficiency
gains. Run-time performances are compared and contrasted, using data sequences
embodying a number of different characteristics. We show that in different
scenarios different data structures are preferable, and that those with the
lowest big O complexity are not always the best performing. We also find that
performance profiles can vary drastically with computational architecture, in a
non-linear fashion.
"

who_suggested: Jonathan Fieldsend

status: happened
---
