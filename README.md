# Ames Housing Price Prediction

This repository contains the code for predicting house prices using machine learning models applied to the Ames Housing dataset. The project involves data exploration, model building, and evaluation of different regression models to understand housing price determinants and create a robust predictive model.

## Project Overview

Predicting housing prices is a valuable task for various stakeholders, including buyers, sellers, and real estate platforms. This project implements and compares three candidate machine learning models:
- **Linear Regression**
- **Regression Tree**
- **k-Nearest Neighbors (k-NN)**

We also experiment with improving the performance of these models by applying:
- Data transformations
- Feature selection
- Model regularization (LASSO)
- Data segmentation based on the house styles

## Dataset

The project uses the **Ames Housing dataset**, which contains detailed information on houses sold in Ames, Iowa. The dataset has 79 features, including both categorical and numerical variables that describe house characteristics, such as:
- Lot size
- Year built
- Neighborhood
- Overall quality
- Basement area, etc.

The target variable is the `SalePrice`, which represents the sale price of the house.

### Dataset Features

- **Target Variable**: `SalePrice`
- **Number of Features**: 79
- **Feature Types**: Numerical and Categorical

## Tasks

### Task 1: Data Exploration
- Understanding the distribution of house prices and exploring relationships between features and the target variable.
- Identifying important features, such as those with the highest correlation with the target variable.
- Creating visualizations to provide insights into the data.

### Task 2: Building Machine Learning Models
- **Preprocessing**: Handling categorical variables, scaling numerical features, and splitting the dataset.
- **Modeling**: Creating and training the following models:
  - Linear Regression (with and without regularization)
  - Regression Tree
  - k-Nearest Neighbors (with feature selection)
- **Evaluation**: Using RMSE to evaluate model performance and understanding the reasons for prediction errors.

### Task 3: Improving Models
- **Data Transformation**: Applying log transformation to the target variable (SalePrice) and using LASSO regularization to improve the Linear Regression model.
- **Data Segmentation**: Building models based on subsets of data, specifically focusing on top house styles (feature: `HouseStyle`).

### Task 4: Results and Insights
- Summarizing the key drivers of housing prices.
- Comparing the predictive performance of the models.
- Assessing the reliability of the predictions and understanding where improvements can be made.

