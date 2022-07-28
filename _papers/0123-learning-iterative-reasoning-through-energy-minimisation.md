---
layout: paper

title: "Learning Iterative Reasoning through Energy Minimization"
authors:
- Yilun Du
- Shuang Li
- Joshua B. Tenenbaum
- Igor Mordatch

venue: "ICML"
year: 2022

link: https://arxiv.org/abs/2206.15448

abstract: "
Deep learning has excelled on complex pattern recognition tasks such as image
classification and object recognition. However, it struggles with tasks
requiring nontrivial reasoning, such as algorithmic computation. Humans are
able to solve such tasks through iterative reasoning -- spending more time
thinking about harder tasks. Most existing neural networks, however, exhibit a
fixed computational budget controlled by the neural network architecture,
preventing additional computational processing on harder tasks. In this work,
we present a new framework for iterative reasoning with neural networks. We
train a neural network to parameterize an energy landscape over all outputs,
and implement each step of the iterative reasoning as an energy minimization
step to find a minimal energy solution. By formulating reasoning as an energy
minimization problem, for harder problems that lead to more complex energy
landscapes, we may then adjust our underlying computational budget by running a
more complex optimization procedure. We empirically illustrate that our
iterative reasoning approach can solve more accurate and generalizable
algorithmic reasoning tasks in both graph and continuous domains. Finally, we
illustrate that our approach can recursively solve algorithmic problems
requiring nested reasoning.
"

who_suggested: George De Ath
status: suggested
---
- [website](https://energy-based-model.github.io/iterative-reasoning-as-energy-minimization/)
- [GitHub](https://github.com/yilundu/irem_code_release)
