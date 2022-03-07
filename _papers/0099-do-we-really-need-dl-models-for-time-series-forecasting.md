---
layout: paper

title: "Do We Really Need Deep Learning Models for Time Series Forecasting?"
authors:
- Shereen Elsayed
- Daniela Thyssens
- Ahmed Rashed
- Hadi Samer Jomaa
- Lars Schmidt-Thieme

venue: "arXiv"
year: 2021

link: https://arxiv.org/abs/2101.02118

abstract: "
Time series forecasting is a crucial task in machine learning, as it has a
wide range of applications including but not limited to forecasting electricity
consumption, traffic, and air quality. Traditional forecasting models rely on
rolling averages, vector auto-regression and auto-regressive integrated moving
averages. On the other hand, deep learning and matrix factorization models have
been recently proposed to tackle the same problem with more competitive
performance. However, one major drawback of such models is that they tend to be
overly complex in comparison to traditional techniques. In this paper, we
report the results of prominent deep learning models with respect to a
well-known machine learning baseline, a Gradient Boosting Regression Tree
(GBRT) model. Similar to the deep neural network (DNN) models, we transform the
time series forecasting task into a window-based regression problem.
Furthermore, we feature-engineered the input and output structure of the GBRT
model, such that, for each training window, the target values are concatenated
with external features, and then flattened to form one input instance for a
multi-output GBRT model. We conducted a comparative study on nine datasets for
eight state-of-the-art deep-learning models that were presented at top-level
conferences in the last years. The results demonstrate that the window-based
input transformation boosts the performance of a simple GBRT model to levels
that outperform all state-of-the-art DNN models evaluated in this paper.
"

who_suggested: George De Ath
status: suggested
---
- [GitHub](https://github.com/Daniela-Shereen/GBRT-for-TSF)
