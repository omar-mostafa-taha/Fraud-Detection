# Fraud detection 

## Project Overview
In this project, we aim to detect fraudulent transactions. By applying data preprocessing techniques, conducting exploratory data analysis, and building classification models, we strive to create accurate predictions.

## Data

Feature Explanation:
distance_from_home: the distance from home where the transaction happened.
distance_from_last_transaction: the distance from when the last transaction happened.
ratio_to_median_purchase_price: ratio of purchased price transaction to median purchase price.
repeat_retailer: Is the transaction happening with the same retailer.
used_chip: Is the transaction through a chip (credit card).
used_pin_number: Is the transaction done using a PIN number.
online_order: Is the transaction an online order.
fraud: Is the transaction fraudulent.

## Exploratory Data Analysis (EDA)
During the exploratory data analysis phase, we delved into the dataset through both univariate and bivariate analysis. We visualized distributions, relationships between variables, and identified patterns that could provide insights for modeling.

## Classification Models

We implemented several classification models to predict fraudulent transactions:

- Decision Tree
- Random Forest
- XGBoost

Each model was trained and evaluated to determine its performance.

## Kaggle
To view the notebook on kaggle please follow the link: https://www.kaggle.com/code/omarmostafataha/credit-card-fraud-detection
