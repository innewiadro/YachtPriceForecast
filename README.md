# YachtPriceForecast
The aim of this project is to find a suitable regression technique that can predict the price of a yacht.

## Table of Contents
* [General Infomation](#general-information)
* [Technologies](#technologies)
* [Features](#features)
* [Setup and Usage](#setup-and-usage)
* [Models](#models)
* [Project Status](#project-status)
* [Sources](#sources)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)


## General Information
The "YachtPriceForecast" project stems from a passion for sailing and the wealth of knowledge acquired both during academic pursuits and in professional endeavors. The driving motivation is to create a tool that aids sailing enthusiasts and professionals in gaining a better understanding of yacht prices. The project aims to utilize various regression techniques available in the scikit-learn library to predict yacht prices with the highest possible accuracy.

Within the project, data is analyzed, sourced from https://www.yachtworld.co.uk, containing information about yachts. Based on this data, regression models are trained, and their objective is to find the optimal way to predict yacht prices.

Unsupervised learning methods are employed in this project, specifically various types of regression, allowing for an understanding of the relationship between different yacht features and their prices.

The goal of this project is not only to predict yacht prices but also to encourage the exploration of various machine learning techniques in the context of analyzing industry data. Future plans involve further refining the project and adding new features to make it even more versatile and useful for the sailing community and potential yacht buyers.
## Technologies
Project is created with:
- python==3.10.12
- beautifulsoup4==4.11.2
- numpy==1.23.5
- pandas==1.5.3
- scikit-learn==1.2.2
- seaborn==0.12.2

- scipy==1.13.3
- yellowbrick==1.5


## Features
- Download data from https://www.yachtworld.co.uk for yachts with selected parameters
- Features for cleaning data from noise and outliners
- Use of the feature importance technique
- Completion of missing data using various techniques
- Explores various model parameters for optimal performance.

## Setup and Usage

This chapter describes how to use your project in Google Colab.

1. **Step 1:** Clone this notebook into your Google Colab account.
2. **Step 2:** Open the notebook in Google Colab.
3. **Step 3:** Follow the steps in the notebook to see the results of your project.

## Models
Models created in this project:
1. *'Linear Regression'*: 

Linear Regression is a fundamental statistical method used for modeling the relationship between a dependent variable and one or more independent variables by fitting a linear equation to observed data. It aims to find the best-fit straight line that predicts the target variable based on the input features.

2. *'Polynomial Regression'*: 

Polynomial Regression extends linear regression by allowing the relationship between the variables to be modeled as an nth-degree polynomial. This allows for a more flexible fit to the data, accommodating curvature and non-linearity in the relationship.

3. *'Ridge Regression'*: 

Ridge Regression is a regularized linear regression technique that mitigates multicollinearity and overfitting by adding a penalty term (L2 regularization) to the linear regression cost function. This penalty term helps to shrink the regression coefficients towards zero, promoting a more stable and generalizable model.

4. *'Lasso'*: 

Lasso (Least Absolute Shrinkage and Selection Operator) is another regularized linear regression technique that adds a penalty term (L1 regularization) to the linear regression cost function. Lasso encourages sparsity in the model by driving some regression coefficients to exactly zero, effectively performing feature selection.

5. *'Decission Tree Regressor'*: 

Decision Tree Regressor is a non-parametric supervised learning method that partitions the feature space into distinct regions and fits a simple model (usually a constant value) to predict the target variable within each region. The tree structure is based on recursive partitioning using feature thresholds.

6. *'ARD Regression'*: 

ARD Regression is a Bayesian linear regression technique that automatically determines the relevance of features in the model by estimating the precision (inverse of variance) of each feature. It effectively performs feature selection by determining which features are most relevant for predicting the target variable.

7. *'Bayesian Ridge Regression'*: 

Bayesian Ridge Regression is a Bayesian variant of linear regression that provides a probabilistic framework for estimating regression coefficients. It introduces priors on the regression coefficients, allowing for uncertainty quantification in the model's predictions.

8. *'Bagging Regressor'*: 

Bagging Regressor, short for Bootstrap Aggregating, is an ensemble learning technique that combines the predictions of multiple base regressors (often decision trees) trained on bootstrapped subsets of the dataset. This aggregation typically reduces overfitting and enhances model robustness and performance.

## Project Status
The project is currently in progress. Future plans include the addition of new features to enhance its capabilities. Stay tuned for updates and exciting enhancements!

## Sources
The data to create the programme are taken from https://www.yachtworld.co.uk/

## Room for Improvement

To do:
- Increasing the amount of data available.
- It is possible to further refine model parameters, explore other machine learning algorithms and test different loss functions to achieve even better price prediction results.
- Perform more advanced feature engineering techniques, such as creating feature interactions, scaling or feature normalisation, which can improve model quality.
- Use ensemble learning techniques, such as bagging, boosting or stacking, to combine different models into a single stronger model, which can effectively increase prediction accuracy.
- Explore and add additional features, such as seasonality, market trends or macro-economic data, to improve predictions and increase understanding of the factors influencing yacht prices.
- Extend the Project with a Web Application: Create an interactive web application that allows users to enter yacht parameters and receive a real-time price prediction, making the project more useful and accessible to a wider audience.

## Contact
Created by [micwoszk@wp.pl] - feel free to contact me!
