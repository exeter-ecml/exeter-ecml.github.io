---
layout: paper

title: "Conservative Objective Models for Effective Offline Model-Based Optimization"
authors:
- Brandon Trabucco
- Aviral Kumar
- Xinyang Geng
- Sergey Levine

venue: ICML
year: 2021

link: http://proceedings.mlr.press/v139/trabucco21a.html

abstract: "
In this paper, we aim to solve data-driven model-based optimization (MBO)
problems, where the goal is to find a design input that maximizes an unknown
objective function provided access to only a static dataset of inputs and their
corresponding objective values. Such data-driven optimization procedures are
the only practical methods in many real-world domains where active data
collection is expensive (e.g., when optimizing over proteins) or dangerous
(e.g., when optimizing over aircraft designs, actively evaluating malformed
aircraft designs is unsafe). Typical methods for MBO that optimize the input
against a learned model of the unknown score function are affected by
erroneous overestimation in the learned model caused due to distributional
shift, that drives the optimizer to low-scoring or invalid inputs. To overcome
this, we propose conservative objective models (COMs), a method that learns a
model of the objective function which lower bounds the actual value of the
ground-truth objective on out-of-distribution inputs and uses it for
optimization. In practice, COMs outperform a number existing methods on a wide
range of MBO problems, including optimizing controller parameters, robot
morphologies, and superconducting materials.
"

who_suggested: George De Ath
status: happened
---
- [Website (including video etc.)](https://sites.google.com/berkeley.edu/coms)
- [Github](https://github.com/brandontrabucco/design-baselines)
