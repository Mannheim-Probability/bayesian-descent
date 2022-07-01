# Bayesian-Descent

## Abstract

While gradient descent is ubiquitous in Machine Learning, there is no adaptive
way to select a learning rate yet. This forces practitioners to do
"hyperparameter tuning". We review how optimization schemes can be motivated
using Taylor approximations and develop intuition why this results in unknown
hyperparameters. We then replace the Taylor approximation with a statistical
Best Linear Unbiased Estimator (BLUE) and derive gradient descent again. But
this time with calculable learning rates.
