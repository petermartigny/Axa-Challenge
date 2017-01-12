# Axa-Challenge
Course Project for Methods for Big Data Analytics @ Ecole polytechnique

## Problem

Axa has $28$ call centers, all having different behavior in time. Predicting in advance the number of incoming calls is of high importance for the labor management. When making predictions, from a business perspective, over-estimations are less damagable than under-estimations. Indeed, over-estimation means loss on the labor costs, but under-estimation means bad customer experience, and eventually client churn, which is far more costly than labor cost loss.

Hence, we use a dyssimetric loss measure: 

$ LinEx(y, \hat {y}) = exp(\alpha (y - \hat {y}) - \alpha (y - \hat {y}) - 1$

with $y$ the true value and $\hat{y}$ the predicted value. Specifically, an value of $0.1$ for the $\alpha$ hyperparameter is used in the computation of the final loss value.
