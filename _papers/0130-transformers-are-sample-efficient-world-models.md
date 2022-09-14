---
layout: paper

title: "Transformers are Sample Efficient World Models"
authors:
- Vincent Micheli
- Eloi Alonso
- François Fleuret

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2209.00588

abstract: "
Deep reinforcement learning agents are notoriously sample inefficient, which
considerably limits their application to real-world problems. Recently, many
model-based methods have been designed to address this issue, with learning in
the imagination of a world model being one of the most prominent approaches.
However, while virtually unlimited interaction with a simulated environment
sounds appealing, the world model has to be accurate over extended periods of
time. Motivated by the success of Transformers in sequence modeling tasks, we
introduce IRIS, a data-efficient agent that learns in a world model composed of
a discrete autoencoder and an autoregressive Transformer. With the equivalent
of only two hours of gameplay in the Atari 100k benchmark, IRIS achieves a mean
human normalized score of 1.046, and outperforms humans on 10 out of 26 games.
Our approach sets a new state of the art for methods without lookahead search,
and even surpasses MuZero. To foster future research on Transformers and world
models for sample-efficient reinforcement learning.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/eloialonso/iris)
