# MachineLearning-Practices
This is a set of practice exercises in Fundamentals of Machine Learning, a subject at HCMUS.

## Homework 1: Linear Regression

[Notebook link](/Week%2001/TruongQuocHuy-21110308-HW1.ipynb)

Dataset relate to how much money a person can get from a mortgage on their home. 

In HW1 notebook, I do:

1. Preprocessing data: Replace null values, remove outliers and normalize data
2. Splitting train-test dataset and implement Linear Regression model which consists of basis Linear Reg, Lasso, Ridge, and ElasticNet.
3. Polynomial Transform

All MAE score is less than 0.01

## Homework 2: Logistic Regression 

[Notebook link](/Week%2002/TruongQuocHuy_21110308_HW2.ipynb)

Objective's homework is classifying a person having heart disease or not. 

Tasks in HW2 is quitely like HW1. I do:

1. Preprocessing data: remove outliers by quantile and normalize data based on feature's distribution
2. Reduction data by dropping feature based on small feature's correlation value
3. Implement Logistic Regression models with different solver and different penalty and compare them by using F1-Score

All F1-Score of classification model is 0.98

## Homework 3: Naive Bayes Classification

[Notebook link](/Week%2003/TruongQuocHuy-21110308-HW3.ipynb)

Using Naive Bayes model to classify the customer buy travel insurance or not. 

All tasks is the same above, plus: Using stack learning method for two model NB which is BernoulliNB for categorical features and GaussianNB for numerical features

So, F1-Score of model is 0.72. This score, compared to tradition method, has been improved

## Homework 4: K-Means - Unsupervised Learning

[Notebook link](/Week%2004/TruongQuocHuy_21110308_HW4.ipynb)

This is pratice which about unsupervised learning. Final goal of Homework is to separate dataset to clusters by using K-Means 

Applying metrics such as Silhouette, Davies-Bouldin, Calinski-Harabasz for meansuring K-Means's performance: 

- Silhouette Score: 0.37
- Davies-Bouldin Index: 1.30
- Calinski-Harabasz Index: 3345.69

Score of three metrics is at an acceptable level. 

## Homework 5: SVM & MLP

[Notebook link](/Week%2005/TruongQuocHuy_21110308_HW5.ipynb)

Using SVM and MLP to classify the imbalance dataset (99.4/1.6)

Best F1-Score of SVM is 0.186. And MLP's is 0.183