# Facebook-Comments-Prediction

## Motivation
The motivation for this project stems from the desire to predict the number of facebook comments on a post within a certain amount of time after posting. Knowing how to predict comments on a post can be seen as a proxy for user engagement which would be interesting to people running ads on Facebook.

## Dataset
The dataused can be found at the following link: https://archive.ics.uci.edu/ml/datasets/Facebook+Comment+Volume+Dataset

## Summary
The goal in this project is to predict the number of comments a Facebook post would get within a certain number of hours after posting. We tried linear and linear models including Lasso Poisson Regression, Forward Stepwise Regression, PCA Poisson Regression and Random Forests. PCA Poisson Regression outperformed all models including the Random Forests models in terms of our key metric RMSE. This is a bit surprising given that neither the linearity nor normality assumptions hold and all of our goodness of fit tests suggest a bad model fit for our linear models.
