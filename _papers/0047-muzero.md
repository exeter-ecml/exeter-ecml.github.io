---
layout: paper

title: "Mastering Atari, Go, chess and shogi by planning with a learned model"
authors:
- Julian Schrittwieser
- Ioannis Antonoglou
- Thomas Hubert
- Karen Simonyan
- Laurent Sifre
- Simon Schmitt
- Arthur Guez
- Edward Lockhart
- Demis Hassabis
- Thore Graepel 
- Timothy Lillicrap
- David Silver

venue: Nature
year: 2020

link: https://www.nature.com/articles/s41586-020-03051-4

abstract: "
Constructing agents with planning capabilities has long been one of the main
challenges in the pursuit of artificial intelligence. Tree-based planning
methods have enjoyed huge success in challenging domains, such as chess and Go,
where a perfect simulator is available. However, in real-world problems, the
dynamics governing the environment are often complex and unknown. Here we
present the MuZero algorithm, which, by combining a tree-based search with a
learned model, achieves superhuman performance in a range of challenging and
visually complex domains, without any knowledge of their underlying dynamics.
The MuZero algorithm learns an iterable model that produces predictions
relevant to planning: the action-selection policy, the value function and the
reward. When evaluated on 57 different Atari games -- the canonical video game
environment for testing artificial intelligence techniques, in which
model-based planning approaches have historically struggled -- the MuZero
algorithm achieved state-of-the-art performance. When evaluated on Go, chess
and shogi—canonical environments for high-performance planning—the MuZero
algorithm matched, without any knowledge of the game dynamics, the superhuman
performance of the AlphaZero algorithm that was supplied with the rules of
the game.
"

who_suggested: George De Ath

status: suggested
---
- Paper: 
    - [Arxiv](https://arxiv.org/abs/1911.08265)
    - [Poster](https://storage.googleapis.com/deepmind-media/research/muzero_poster_neurips_2019.pdf)
- Blog posts: 
    - [DeepMind](https://deepmind.com/blog/article/muzero-mastering-go-chess-shogi-and-atari-without-rules)
    - [First author](http://www.furidamu.org/blog/2020/12/22/muzero-intuition/)
- Talks: 
    - [NeurIPS (9min)](https://www.youtube.com/watch?v=vt5jOSy7cz8&t=2s)
    - [ICAPS (30min)](https://www.youtube.com/watch?v=L0A86LmH7Yw)
