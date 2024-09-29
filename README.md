# FindDefault

A data science project to predict credit card transaction frauds using machine learning model.


## Problem Statement

A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

We have to build a classification model to predict whether a transaction is fraudulent or not.


## Implementation Strategy

**Exploratory Data Analysis:** Analyze and understand the data to identify patterns, relationships, and trends in the data by using Descriptive Statistics and Visualizations. 

**Data Preparation:** This might include standardization, handling the missing values and outliers in the data. 
Dealing with Imbalanced data: This data set is highly imbalanced. The data should be balanced using the appropriate methods before moving onto model building.

**Feature Engineering:** Transform the existing features for better performance of the ML Models. 

**Model Selection:** Choose the most appropriate model that can be used for this project. 

**Model Training:** Split the data into train & test sets and use the train set to estimate the best model parameters. 

**Model Evaluation:** Evaluate the performance of the model on data that was not used during the training process. The goal is to estimate the model's ability to generalize to new, unseen data and to identify any issues with the model, such as overfitting. 


## Conclusions

The data is highly unbalanced, however it was possible to make all the required analysis, prepare the data and create a highly accurate machine learning model. The model can now be used to predict the fraudulent & legitimate transactions from a given dataset.