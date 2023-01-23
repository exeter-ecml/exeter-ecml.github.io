---
layout: paper

title: "On the role of Model Uncertainties in Bayesian Optimization"

authors:
- Jonathan Foldager
- Mikkel Jordahn
- Lars Kai Hansen
- Michael Riis Andersen

venue: "arXiv"

year: 2023

link: https://arxiv.org/abs/2301.05983

abstract: "
Bayesian optimization (BO) is a popular method for black-box optimization,
which relies on uncertainty as part of its decision-making process when
deciding which experiment to perform next. However, not much work has addressed
the effect of uncertainty on the performance of the BO algorithm and to what
extent calibrated uncertainties improve the ability to find the global optimum.
In this work, we provide an extensive study of the relationship between the BO
performance (regret) and uncertainty calibration for popular surrogate models
and compare them across both synthetic and real-world experiments. Our results
confirm that Gaussian Processes are strong surrogate models and that they tend
to outperform other popular models. Our results further show a positive
association between calibration error and regret, but interestingly, this
association disappears when we control for the type of model in the analysis.
We also studied the effect of re-calibration and demonstrate that it generally
does not lead to improved regret. Finally, we provide theoretical justification
for why uncertainty calibration might be difficult to combine with BO due to
the small sample sizes commonly used.
"

who_suggested: George De Ath
status: suggested
---
