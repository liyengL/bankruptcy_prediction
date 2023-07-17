# Bankruptcy Prediction Model

This is a project during my graduate studies using machine learning to predict bankruptcy in Spain. 

## Introduction

This machine learning model predicts the likelihood of bankruptcy by analyzing historical financial data. It helps identify companies facing financial distress or at risk of going bankrupt.

## Dataset

The dataset contains 106057 rows and 52 columns. Moreover, when it comes to the dependent variable, status, it has 100'000 instances of 0 and 6057 instances of 1. 

## Data Exploration

An in-depth analysis of the dataset was conducted, including descriptive statistics and visualizations, to gain insights into its characteristics and understand the distribution of bankruptcy instances.


## Data Cleaning

Thorough data cleaning procedures were performed to handle missing values, outliers, and ensure data consistency.

### Missing Values

Missing values in the dataset were addressed. We first cleaned the missing data based on the columns. Then, we observed that some companies contain many missing columns. To address this, we perform some threshold trial to see the best way to clean this data. 

### Dealing with Outliers

Outliers were analyzed, and it was observed that removing them might negatively impact the model. Therefore, the outliers were not dealt with, and their impact on the model's performance was evaluated.

### Correlation Check

A correlation matrix was examined, highlighting strong linear relationships between financial ratios and growth rates. These correlations provide insights into a company's financial health and performance.


## Model Evaluation

As we have a large dataset, we decided to divide the dataset based on different years and trained the model. We have trained a model for year 2013, 2014, 2015 and 2016. To avoid overfitting, we have tested the model with the following years. The model's performance was evaluated using various metrics, such as accuracy, precision and recall.

## Interpretation

The interpretation of the model is done by tree and shapley values. 

## Application 

This model is especially useful for consulting firms or banks when dealing with loans for companies. 


