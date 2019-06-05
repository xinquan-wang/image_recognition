### [Project Description]

This project will implement 10 machine learning models to solve image recognition problem. We will also evaluate the models' performance in terms of model type, sample size and running time, and further discuss their pros and cons.

The dataset we used is a set of images for different types of apparel from Zalando's article, consisting of a training set of 60,000 examples and a test set of 10,000 examples. The original dataset divided each image into 784 (28 by 28) pixels. And in our project, we have condensed these data into 49 pixels (7 by 7) per image to simplify the computations. For each dataset, we have a column called label which indicates the type of the product and 49 columns for pixels, Denoted as pixels1, pixels2, ... ,pixels49, these pixels columns provide the measurement for the images in grayscale.

To solve the challenge, we first generate 9 different samples with 3 different sizes and 3 iterations respectively. For each sample, we applied the following 10 models to generate the predictive classification results.

-- Ridge Regression  
-- K-Nearest Neighbors  
-- Classification Tree  
-- Support Vector Machines  
-- Lasso Regression  
-- Multinomial logistic regression  
-- Random Forest  
-- Generalized Boosted Regression Models - gbm  
-- Generalized Boosted Regression Models - xgboost  
-- Ensemble model

In order to evaluate their quality, we introduced a score function by balancing the sample size, running time and prediction accuracy. Based on these results, we made some comparisons between these models, identifying the "best" model for our dataset.
