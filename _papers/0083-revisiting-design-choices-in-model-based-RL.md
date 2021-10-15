---
layout: paper

title: "Revisiting Design Choices in Model-Based Offline Reinforcement Learning"
authors:
- Cong Lu
- Philip J. Ball
- Jack Parker-Holder
- Michael A. Osborne
- Stephen J. Roberts
venue: RL4RealLife Workshop @ ICML
year: 2021

link: https://arxiv.org/abs/2106.00311

abstract: "
Offline reinforcement learning enables agents to leverage large pre-collected
datasets of environment transitions to learn control policies, circumventing
the need for potentially expensive or unsafe online data collection.
Significant progress has been made recently in offline model-based
reinforcement learning, approaches which leverage a learned dynamics model.
This typically involves constructing a probabilistic model, and using the model
uncertainty to penalize rewards where there is insufficient data, solving for a
pessimistic MDP that lower bounds the true MDP. Existing methods, however,
exhibit a breakdown between theory and practice, whereby pessimistic return
ought to be bounded by the total variation distance of the model from the true
dynamics, but is instead implemented through a penalty based on estimated model
uncertainty. This has spawned a variety of uncertainty heuristics, with little
to no comparison between differing approaches. In this paper, we compare these
heuristics, and design novel protocols to investigate their interaction with
other hyperparameters, such as the number of models, or imaginary rollout
horizon. Using these insights, we show that selecting these key hyperparameters
using Bayesian Optimization produces superior configurations that are vastly
different to those currently used in existing hand-tuned state-of-the-art
methods, and result in drastically stronger performance.
"

who_suggested: George De Ath
status: suggested
---
- [twitter thread](https://twitter.com/philipjohnball/status/1447952141067472902)
