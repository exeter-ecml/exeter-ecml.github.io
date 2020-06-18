---
layout: paper

title: "NGBoost: Natural Gradient Boosting for Probabilistic Prediction"
authors:
- Tony Duan
- Anand Avati
- Daisy Yi Ding
- Khanh K. Thai
- Sanjay Basu
- Andrew Y. Ng
- Alejandro Schuler
venue: Proceedings of the 37th International Conference on Machine Learning
year: 2020

link: https://arxiv.org/abs/2006.07990

abstract: "
We present Natural Gradient Boosting (NGBoost), an algorithm for generic 
probabilistic prediction via gradient boosting. Typical regression models
return a point estimate, conditional on covariates, but probabilistic
regression models output a full probability distribution over the outcome
space, conditional on the covariates. This allows for predictive uncertainty
estimation -- crucial in applications like healthcare and weather forecasting.
NGBoost generalizes gradient boosting to probabilistic regression by treating
the parameters of the conditional distribution as targets for a multiparameter
boosting algorithm. Furthermore, we show how the Natural Gradient is required
to correct the training dynamics of our multiparameter boosting approach. 
NGBoost can be used with any base learner, any family of distributions with 
continuous parameters, and any scoring rule. NGBoost matches or exceeds the
performance of existing methods for probabilistic prediction while offering
additional benefits in flexibility, scalability, and usability.
"

who_suggested: George De Ath

status: suggested
---
Further information: <https://stanfordmlgroup.github.io/projects/ngboost/>

Github: <https://github.com/stanfordmlgroup/ngboost>

User guide: <https://stanfordmlgroup.github.io/ngboost/intro.html>