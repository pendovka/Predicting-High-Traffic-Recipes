# Recipe Traffic Predictor

## Introduction
This project aims to predict recipes that gain high user traffic. We analyze a dataset containing recipe information and binary variables indicating high or low user traffic.

## Data Processing
- Validate and manipulate data, including handling missing values and changing column data types.
- Explore nutritional features, identify outliers, and implement algorithms for outlier removal.

## Exploratory Data Analysis (EDA)
- Construct plots to examine relationships between nutritional values and recipe popularity.
- Explore associations between recipe categories and high user traffic.

## Model Preprocessing
- Apply log transformation to achieve a more Gaussian-like distribution of numeric variables.
- One-Hot Encoding for 'Category' and Label Encoding for the response variable.
- Feature scaling to ensure consistent scales for numeric variables.

## Key Metrics
Our key metric is precision, prioritizing the accurate selection of popular recipes for showcasing on the main page.

## Model Selection
- Test three models: K-Nearest Neighbours, Logistic Regression, and Gradient Boosting Tree.
- Tuned each model with an optimized set of hyperparameters. 

## Results
- Gradient Boosting Tree consistently achieves over 80% precision consistently.
- Feature importance analysis reveals categories that drive high traffic.

## Conclusion
Picking top-performing recipes from categories like 'Vegetable' and 'Pork' proves strategic for maximizing user engagement.
