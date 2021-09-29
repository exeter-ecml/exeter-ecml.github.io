---
layout: paper

title: "Training BatchNorm and Only BatchNorm: On the Expressive Power of Random Features in CNNs"
authors:
- Jonathan Frankle
- David J. Schwab
- Ari S. Morcos
venue: ICLR
year: 2021

link: https://openreview.net/pdf?id=vYeQQ29Tbvx

abstract: "
A wide variety of deep learning techniques from style transfer to multitask
learning rely on training affine transformations of features. Most prominent
among these is the popular feature normalization technique BatchNorm, which
normalizes activations and then subsequently applies a learned affine 
transform. In this paper, we aim to understand the role and expressive power of
affine parameters used to transform features in this way. To isolate the
contribution of these parameters from that of the learned features they
transform, we investigate the performance achieved when training only these
parameters in BatchNorm and freezing all weights at their random
initializations. Doing so leads to surprisingly high performance considering
the significant limitations that this style of training imposes. For example,
sufficiently deep ResNets reach 82% (CIFAR-10) and 32% (ImageNet, top-5)
accuracy in this configuration, far higher than when training an equivalent
number of randomly chosen parameters elsewhere in the network. BatchNorm
achieves this performance in part by naturally learning to disable around a
third of the random features. Not only do these results highlight the
expressive power of affine parameters in deep learning, but - in a broader
sense - they characterize the expressive power of neural networks constructed
simply by shifting and rescaling random features.
"

who_suggested: George De Ath
status: suggested
---
- [Reviews](https://openreview.net/forum?id=vYeQQ29Tbvx)
- [Non-author report on the paper](https://wandb.ai/production/2ff677a71/sayakpaul/training-bn-only/reports/The-Power-of-Random-Features-of-a-CNN--VmlldzoxMTIxODA)
- [Report code](https://github.com/sayakpaul/Training-BatchNorm-and-Only-BatchNorm/)
