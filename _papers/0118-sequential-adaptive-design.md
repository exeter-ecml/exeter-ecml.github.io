---
layout: paper

title: "Sequential adaptive design for emulating costly computer codes"
authors:
- Hossein Mohammadi
- Peter Challenor

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2206.12113

abstract: "
Gaussian processes (GPs) are generally regarded as the gold standard surrogate
model for emulating computationally expensive computer-based simulators.
However, the problem of training GPs as accurately as possible with a minimum
number of model evaluations remains a challenging task. We address this problem
by suggesting a novel adaptive sampling criterion called VIGF (variance of
improvement for global fit). It is the variance of an improvement function
which is defined at any location as the square of the difference between the
fitted GP emulator and the model output at the nearest site in the current
design. At each iteration of the proposed algorithm, a new run is performed
where the VIGF criterion is the largest. Then, the new sample is added to the
design and the emulator is updated accordingly. The batch version of VIGF is
also proposed which can save the user time when parallel computing is
available. The applicability of our method is assessed on a number of test
functions and its performance is compared with several sequential sampling
strategies. The results suggest that our method has a superior performance in
predicting the benchmarking functions in most cases.
"

who_suggested: George De Ath
status: happened
---
