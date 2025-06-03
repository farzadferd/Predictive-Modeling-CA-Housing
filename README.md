## California Housing Predictive Modeling

# Overview

This project analyzes the California Housing dataset to predict median house values across California districts. Using exploratory data analysis and regression modeling techniques such as Ridge Regression, the project investigates key features impacting housing prices and evaluates model performance.

# Objectives

Explore and preprocess the California Housing dataset to identify influential features.
Visualize data distributions, correlations, and geographic patterns.
Implement Ridge Regression models with and without feature standardization.
Evaluate models through cross-validation and compare predictive accuracy.
Interpret regression coefficients to understand feature importance.

# Approach

1. Data Exploration
   
Loaded and cleaned the California Housing dataset.
Examined variable distributions and identified skewness, outliers, and bimodal features.
Created histograms, scatterplots, correlation matrices, and geographic maps.

2. Modeling
   
Built baseline Ridge Regression without standardizing features.
Standardized features and retrained Ridge Regression for improved comparability.
Performed cross-validation to assess model performance.
Selected features based on their predictive power.

3. Evaluation and Interpretation
   
Compared cross-validation errors between standardized and non-standardized models.
Interpreted model coefficients to identify the strongest predictors of house prices.
Visualized geographic trends relating to median income and housing values.

# Key Learnings about the Data
Median income, house age, and average room count are strong predictors of median house value.
Geographic features (latitude and longitude) show distinct regional housing price patterns.
Skewed and bimodal distributions in features require careful preprocessing.

# Key Learnings about the Approach
Ridge Regression effectively reduces overfitting by regularizing coefficients.
Standardizing features improves model stability and interpretability.
Cross-validation provides reliable estimates of model generalization.
Visualizing data geographically reveals regional effects on housing prices.

# Tools Used:
Python

scikit-learn for Ridge Regression and model evaluation

pandas, numpy for data processing

matplotlib, seaborn for visualizations

geopandas and contextily for geographic mapping
