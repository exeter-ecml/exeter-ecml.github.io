---
layout: paper

title: "Unsupervised Learning of Visual Features by Contrasting Cluster Assignments"
authors:
- Mathilde Caron
- Ishan Misra
- Julien Mairal
- Priya Goyal
- Piotr Bojanowski
- Armand Joulin

venue: "NeurIPS"
year: 2020

link: https://proceedings.neurips.cc/paper/2020/hash/70feb62b69f16e0238f741fab228fec2-Abstract.html

abstract: "
Unsupervised image representations have significantly reduced the gap with
supervised pretraining, notably with the recent achievements of contrastive
learning methods. These contrastive methods typically work online and rely on a
large number of explicit pairwise feature comparisons, which is computationally
challenging. In this paper, we propose an online algorithm, SwAV, that takes
advantage of contrastive methods without requiring to compute pairwise
comparisons. Specifically, our method simultaneously clusters the data while
enforcing consistency between cluster assignments produced for different
augmentations (or views) of the same image, instead of comparing features
directly as in contrastive learning. Simply put, we use a swapped prediction
mechanism where we predict the code of a view from the representation of
another view. Our method can be trained with large and small batches and can
scale to unlimited amounts of data. Compared to previous contrastive methods,
our method is more memory efficient since it does not require a large memory
bank or a special momentum network. In addition, we also propose a new data
augmentation strategy, multi-crop, that uses a mix of views with different
resolutions in place of two full-resolution views, without increasing the
memory or compute requirements. We validate our findings by achieving 75.3%
top-1 accuracy on ImageNet with ResNet-50, as well as surpassing supervised
pretraining on all the considered transfer tasks.
"

who_suggested: Abhra Chaudhuri
status: happened
---
- [NeurIPS talk (3min)](https://slideslive.com/38936001/unsupervised-learning-of-visual-features-by-contrasting-cluster-assignments)
- [Longer talk (45min)](https://www.youtube.com/watch?v=zffVe7TTx2I)
- [Short blog post](https://ai.facebook.com/blog/high-performance-self-supervised-image-classification-with-contrastive-clustering/)
- [Long blog post](https://wandb.ai/authors/swav-tf/reports/Unsupervised-visual-representation-learning-with-SwAV--VmlldzoyMjg3Mzg)
- [Video chat with main author (30min)](https://www.youtube.com/watch?v=7QmsTleiRLs)
- [Video about the loss function (15min)](https://www.youtube.com/watch?v=M_DgS3XGeJc)
- [ML Street Talk video (1hr30min)](https://www.youtube.com/watch?v=uqJ2hbDGHjY)
- [github (pytorch)](https://github.com/facebookresearch/swav)
- [github (tensorflow)](https://github.com/ayulockin/SwAV-TF)
