# Online Shoppers Purchasing Behavior

## Introduction and Goal:

Welcome to the Online Shoppers Purchasing Behavior project, where we analyze a dataset containing various predictor variables related to customer visits to an e-commerce website. Our goal is to identify revenue-generating customers and target them effectively to optimize marketing strategies and enhance sales performance.

## Dataset:

The data is a collection of various predictor variables related to a session of a customer's visit to an e-commerce website. Some features of the data :

### 1. Multivariate:

The dataset is multi-variate, consisting of a combination of numerical and categorical features.

### 2. Binary Response Variable:

The response variable indicates whether a customer generated revenue during their visit, with True or False values.

### 3. Imbalanced Data:

The dataset exhibits class imbalance, with a significantly lower proportion of customers generating revenue compared to those who do not.

## Data Analysis:

Our primary objective is to identify revenue-generating customers and develop a predictive model that maximizes the identification of true positives. To address the imbalance in the data, we perform oversampling. We explore various regression models, including logistic regression, random forest, and lasso regression, aiming to achieve high sensitivity (true positive rates). Our analysis reveals that the lasso regression model demonstrates the highest sensitivity at 88.3%.

## Highlights:

### 1. Oversampling of Data:

We employ oversampling techniques to address the class imbalance in the dataset.

### 2. Multiple Regression Models:

We explore and compare multiple regression models to identify the best-performing model for predicting revenue-generating customers.

## Report and Code:

The detailed report for this analysis is available in the file named "Online Shoppers Purchasing Behavior.pdf". The code for data analysis and model development is provided in two Python script files: "OnlineShoppersPurchasingBehavior_code_Part1.py" and "OnlineShoppersPurchasingBehavior_code_Part2.py".


