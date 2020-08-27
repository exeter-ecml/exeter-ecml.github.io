---
layout: paper

title: Knowing The What But Not The Where in Bayesian Optimization
authors:
- Vu Nguyen
- Michael A Osborne
venue: Proceedings of the 37th International Conference on Machine Learning
year: 2020
link: https://proceedings.icml.cc/paper/2020/file/0abdc563a06105aee3c6136871c9f4d1-Paper.pdf

abstract: "
Bayesian optimization has demonstrated impressive success in finding the
optimum input $$x^*$$ and output $$f^* = f(x^* ) = \\text{max} \\, f(x)$$ of a
black-box function $$f^*$$. In some applications, however, the optimum output 
$$f^*$$ is known in advance and the goal is to find the corresponding optimum
input $$x^*$$. In this paper, we consider a new setting in BO in which the
knowledge of the optimum output $$f^*$$ is available. Our goal is to exploit
the knowledge about $$f^*$$ to search for the input $$x^*$$ efficiently. To
achieve this goal, we first transform the Gaussian process surrogate using the
information about the optimum output. Then, we propose two acquisition
functions, called confidence bound minimization and expected regret
minimization. We show that our approaches work intuitively and give
quantitatively better performance against standard BO methods. We demonstrate
real applications in tuning a deep reinforcement learning algorithm on the
CartPole problem and XGBoost on Skin Segmentation dataset in which the optimum
values are publicly available.
"

who_suggested: George De Ath

status: suggested
---
- [Presentation](https://slideslive.com/38927867/)
- [Slides](https://icml.cc/media/Slides/icml/2020/virtual(no-parent)-14-21-00UTC-6137-knowing_the_wha.pdf)
- [Supplementary material](https://proceedings.icml.cc/paper/2020/file/0abdc563a06105aee3c6136871c9f4d1-Supplemental.pdf)
- [Code](https://github.com/ntienvu/KnownOptimum_BO)