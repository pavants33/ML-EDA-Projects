Pokemon Dataset Analysis and Classification

Overview

This project focuses on exploring and analyzing the Pokemon dataset to classify whether a Pokemon is legendary or not based on various features. The dataset contains 23 columns comprising both numeric and categorical data, with 'isLegendary' serving as the target variable.

Features

Data Import and Visualization: Utilized libraries such as Pandas, NumPy, Matplotlib, Seaborn, Plotly for data manipulation, visualization, and missing data analysis.
Univariate Analysis: Explored each column to gain insights into distributions and patterns within attributes like Type 1, Egg Group 1, Male Probability (Pr_Male), Body Style, Color, and more.
Exploratory Data Analysis: Investigated correlations, distributions, and outliers for features like HP, Attack, Defense, Height, Weight, Mega Evolution, and Body Style.
Statistical Analysis: Compared and visualized attributes such as Type, Egg Group, and Color among Pokemon with the lowest catch rates.
Feature Engineering: Preprocessed data by handling missing values, encoding categorical variables, and scaling numeric features to prepare for machine learning models.
Machine Learning Models: Implemented various classifiers including Logistic Regression, Random Forest, LGBM, XGBoost, and CatBoost, evaluated using K-fold cross-validation for accuracy and AUC scores.
Model Comparison: Compared the performance of different models based on cross-validated accuracy and AUC scores.


Results

Identified top features influencing a Pokemon's legendary status.
Established insights into Pokemon types, attributes, and characteristics associated with low catch rates.
Achieved high accuracy and AUC scores with machine learning models, demonstrating effective classification of legendary Pokemon.

Conclusion

This project provides a comprehensive analysis of Pokemon data, highlighting significant features and patterns using exploratory and predictive techniques. The results underscore the predictive capabilities of machine learning in distinguishing legendary Pokemon based on their attributes.
