---
layout: paper

title: "HesScale: Scalable Computation of Hessian Diagonals"

authors:
- Mohamed Elsayed
- A. Rupam Mahmood

venue: "arXiv (ICLR 2023 submission)"

year: 2022

link: https://openreview.net/forum?id=mKILD5MLR2C

abstract: "
Second-order optimization uses curvature information about the objective
function, which can help in faster convergence. However, such methods typically
require expensive computation of the Hessian matrix, preventing their usage in
a scalable way. The absence of efficient ways of computation drove the most
widely used methods to focus on first-order approximations that do not capture
the curvature information. In this paper, we develop *HesScale*, a
scalable approach to approximating the diagonal of the Hessian matrix, to
incorporate second-order information in a computationally efficient manner. We
show that HesScale has the same computational complexity as backpropagation.
Our results on supervised classification show that HesScale achieves high
approximation accuracy, allowing for scalable and efficient second-order
optimization.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/mohmdelsayed/HesScale)
