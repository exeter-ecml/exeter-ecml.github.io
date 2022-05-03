---
layout: paper

title: "It's DONE: Direct ONE-shot learning without training optimization"
authors:
- Kazufumi Hosoda
- Keigo Nishida
- Shigeto Seno
- Tomohiro Mashita
- Hideki Kashioka
- zumi Ohzawa

venue: "arXiv"
year: 2022

link: https://arxiv.org/abs/2204.13361

abstract: "
Learning a new concept from one example is a superior function of human brain
and it is drawing attention in the field of machine learning as one-shot
learning task. In this paper, we propose the simplest method for this task,
named Direct ONE-shot learning (DONE). DONE adds a new class to a pretrained
deep neural network (DNN) classifier with neither training optimization nor
other-classes modification. DONE is inspired by Hebbian theory and directly
uses the neural activity input of the final dense layer obtained from a data
that belongs to the new additional class as the connectivity weight (synaptic
strength) with a newly-provided-output neuron for the new class. DONE requires
just one inference for obtaining the output of the final dense layer and its
procedure is simple, deterministic, not requiring parameter tuning and
hyperparameters. The performance of DONE depends entirely on the pretrained
DNN model used as a backbone model, and we confirmed that DONE with a
well-trained backbone model performs a practical-level accuracy. DONE has some
advantages including a DNN's practical use that is difficult to spend high
cost for a training, an evaluation of existing DNN models, and the
understanding of the brain. DONE might be telling us one-shot learning is an
easy task that can be achieved by a simple principle not only for humans but
also for current well-trained DNN models.
"

who_suggested: George De Ath
status: suggested
---
NeurIPS 2022 submission.
