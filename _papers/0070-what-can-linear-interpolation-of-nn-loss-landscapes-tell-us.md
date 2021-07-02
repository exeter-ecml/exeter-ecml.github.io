---
layout: paper

title: "What can linear interpolation of neural network loss landscapes tell us?"
authors:
- Tiffany Vlaar
- Jonathan Frankle

venue: arXiv
year: 2021

link: https://arxiv.org/abs/2106.16004

abstract: "
Studying neural network loss landscapes provides insights into the nature of
the underlying optimization problems. Unfortunately, loss landscapes are
notoriously difficult to visualize in a human-comprehensible fashion. One
common way to address this problem is to plot linear slices of the landscape,
for example from the initial state of the network to the final state after
optimization. On the basis of this analysis, prior work has drawn broader
conclusions about the difficulty of the optimization problem. In this paper, we
put inferences of this kind to the test, systematically evaluating how linear
interpolation and final performance vary when altering the data, choice of 
initialization, and other optimizer and architecture design choices. Further,
we use linear interpolation to study the role played by individual layers and
substructures of the network. We find that certain layers are more sensitive to
the choice of initialization and optimizer hyperparameter settings, and we
exploit these observations to design custom optimization schemes. However, our
results cast doubt on the broader intuition that the presence or absence of
barriers when interpolating necessarily relates to the success of optimization.
"

who_suggested: George De Ath
status: suggested
---
