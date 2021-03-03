---
layout: paper

title: "On Sequential Online Archiving of Objective Vectors"
authors:
- Manuel López-Ibáñez
- Joshua Knowles
- Marco Laumanns
venue: Evolutionary Multi-Criterion Optimization (EMO)
year: 2011

link: http://iridia.ulb.ac.be/IridiaTrSeries/link/IridiaTr2011-001.pdf

abstract: "
In this paper, we examine the problem of maintaining an approximation of the
set of nondominated points visited during a multiobjective optimization, a
problem commonly known as archiving. Most of the currently available archiving
algorithms are reviewed, and what is known about their convergence and
approximation properties is summarized. The main scenario considered is the
restricted case where the archive must be updated online as points are
generated one by one, and at most a fixed number of points are to be stored in
the archive at any one time. In this scenario, the ⊲-monotonicity of an
archiving algorithm is proposed as a weaker, but more practical, property than
negative efficiency preservation. This paper shows that hypervolume-based
archivers and a recently proposed multi-level grid archiver have this
property. On the other hand, the archiving methods used by SPEA2 and NSGA-II do
not, and they may ⊲-deteriorate with time. The ⊲-monotonicity property has
meaning on any input sequence of points. We also classify archivers according
to limit properties, i.e. convergence and approximation properties of the
archiver in the limit of infinite (input) samples from a finite space with
strictly positive generation probabilities for all points. This paper
establishes a number of research questions, and provides the initial framework
and analysis for answering them. 
"

who_suggested: Jonathan Fieldsend

status: happened
---
