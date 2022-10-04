---
layout: paper

title: "Learning to Learn with Generative Models of Neural Network Checkpoints"
authors:
- William Peebles
- Ilija Radosavovic
- Tim Brooks
- Alexei A. Efros,
- Jitendra Malik

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2209.12892

abstract: "
We explore a data-driven approach for learning to optimize neural networks. We
construct a dataset of neural network checkpoints and train a generative model
on the parameters. In particular, our model is a conditional diffusion
transformer that, given an initial input parameter vector and a prompted loss,
error, or return, predicts the distribution over parameter updates that
achieve the desired metric. At test time, it can optimize neural networks with
unseen parameters for downstream tasks in just one update. We find that our
approach successfully generates parameters for a wide range of loss prompts.
Moreover, it can sample multimodal parameter solutions and has favorable
scaling properties. We apply our method to different neural network
architectures and tasks in supervised and reinforcement learning.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://www.github.com/wpeebles/G.pt)
- [Project page](https://www.wpeebles.com/Gpt)
- [Twitter thread](https://twitter.com/billpeeb/status/1574850991001772032)
