---
layout: paper

title: "Model soups: averaging weights of multiple fine-tuned models improves accuracy without increasing inference time"
authors:
- Mitchell Wortsman
- Gabriel Ilharco
- Samir Yitzhak Gadre
- Rebecca Roelofs
- Raphael Gontijo-Lopes
- Ari S. Morcos
- Hongseok Namkoong
- Ali Farhadi
- Yair Carmon
- Simon Kornblith
- Ludwig Schmidt

venue: "ICML 2022"
year: 2022

link: https://arxiv.org/abs/2203.05482

abstract: "
The conventional recipe for maximizing model accuracy is to (1) train multiple
models with various hyperparameters and (2) pick the individual model which
performs best on a held-out validation set, discarding the remainder. In this
paper, we revisit the second step of this procedure in the context of
fine-tuning large pre-trained models, where fine-tuned models often appear to
lie in a single low error basin. We show that averaging the weights of multiple
models fine-tuned with different hyperparameter configurations often improves
accuracy and robustness. Unlike a conventional ensemble, we may average many
models without incurring any additional inference or memory costs -- we call
the results *model soups*. When fine-tuning large pre-trained models such as
CLIP, ALIGN, and a ViT-G pre-trained on JFT, our soup recipe provides
significant improvements over the best model in a hyperparameter sweep on
ImageNet. As a highlight, the resulting ViT-G model attains 90.94% top-1
accuracy on ImageNet, a new state of the art. Furthermore, we show that the
model soup approach extends to multiple image classification and natural
language processing tasks, improves out-of-distribution performance, and
improves zero-shot performance on new downstream tasks. Finally, we
analytically relate the performance similarity of weight-averaging and
logit-ensembling to flatness of the loss and confidence of the predictions,
and validate this relation empirically.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/mlfoundations/model-soups)
- [twitter thread](https://twitter.com/mitchnw/status/1539992200943005696)
