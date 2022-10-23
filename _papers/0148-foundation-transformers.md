---
layout: paper

title: "Foundation Transformers"
authors:
- Hongyu Wang
- Shuming Ma
- Shaohan Huang
- Li Dong
- Wenhui Wang
- Zhiliang Peng
- Yu Wu
- Payal Bajaj
- Saksham Singhal
- Alon Benhaim
- Barun Patra
- Zhun Liu
- Vishrav Chaudhary
- Xia Song
- Furu Wei

venue: "arXiv"

year: 2022

link: https://arxiv.org/abs/2009.06732

abstract: "
A big convergence of model architectures across language, vision, speech, and
multimodal is emerging. However, under the same name 'Transformers', the above
areas use different implementations for better performance, e.g.,
Post-LayerNorm for BERT, and Pre-LayerNorm for GPT and vision Transformers. We
call for the development of Foundation Transformer for true general-purpose
modeling, which serves as a go-to architecture for various tasks and modalities
with guaranteed training stability. In this work, we introduce a Transformer
variant, named Magneto, to fulfill the goal. Specifically, we propose
Sub-LayerNorm for good expressivity, and the initialization strategy
theoretically derived from DeepNet for stable scaling up. Extensive experiments
demonstrate its superior performance and better stability than the de facto
Transformer variants designed for various applications, including language
modeling (i.e., BERT, and GPT), machine translation, vision pretraining (i.e.,
BEiT), speech recognition, and multimodal pretraining (i.e., BEiT-3).
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/microsoft/unilm)
- [Project page](https://gitnlp.org/agi/index.html)
