---
layout: paper

title: Predicting the outputs of finite networks trained with noisy gradients
authors:
- Gadi Naveh
- Oded Ben-David
- Haim Sompolinsky
- Zohar Ringel
venue: arXiv
year: 2020
link: https://arxiv.org/abs/2004.01190

abstract: "
A recent line of studies has focused on the infinite width limit of deep neural
networks (DNNs) where, under a certain deterministic training protocol, the DNN
outputs are related to a Gaussian Process (GP) known as the Neural Tangent
Kernel (NTK). However, finite-width DNNs differ from GPs quantitatively and for
CNNs the difference may be qualitative. Here we present a DNN training protocol
involving noise whose outcome is mappable to a certain non-Gaussian stochastic
process. An analytical framework is then introduced to analyze this resulting
non-Gaussian process, whose deviation from a GP is controlled by the finite
width. Our work extends upon previous relations between DNNs and GPs in several
ways: (a) In the infinite width limit, it establishes a mapping between DNNs
and a GP different from the NTK. (b) It allows computing analytically the
general form of the finite width correction (FWC) for DNNs with arbitrary
activation functions and depth and further provides insight on the magnitude
and implications of these FWCs. (c) It appears capable of providing better
performance than the corresponding GP in the case of CNNs. We are able to
predict the outputs of empirical finite networks with high accuracy, improving
upon the accuracy of GP predictions by over an order of magnitude. Overall, we
provide a framework that offers both an analytical handle and a more faithful
model of real-world settings than previous studies in this avenue of research.
"

who_suggested: George De Ath

status: suggested
---
