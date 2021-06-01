---
layout: paper

title: "Deep Evidential Regression"
authors:
- Alexander Amini
- Wilko Schwarting
- Ava Soleimany
- Daniela Rus

venue: NeurIPS
year: 2020

link: https://proceedings.neurips.cc/paper/2020/hash/aab085461de182608ee9f607f3f7d18f-Abstract.html

abstract: "
Deterministic neural networks (NNs) are increasingly being deployed in safety
critical domains, where calibrated, robust, and efficient measures of
uncertainty are crucial. In this paper, we propose a novel method for training 
non-Bayesian NNs to estimate a continuous target as well as its associated
evidence in order to learn both aleatoric and epistemic uncertainty. We
accomplish this by placing evidential priors over the original Gaussian
likelihood function and training the NN to infer the hyperparameters of the
evidential distribution. We additionally impose priors during training such
that the model is regularized when its predicted evidence is not aligned with
the correct output. Our method does not rely on sampling during inference or on
out-of-distribution (OOD) examples for training, thus enabling efficient and
scalable uncertainty learning. We demonstrate learning well-calibrated measures
of uncertainty on various benchmarks, scaling to complex computer vision tasks,
as well as robustness to adversarial and OOD test samples.
"

who_suggested: George De Ath
status: suggested
---
- [Code](https://github.com/aamini/evidential-deep-learning)
