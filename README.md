# House Price Prediction Using Linear Regression

## Overview

This project focuses on predicting house prices using a linear regression model. The dataset, sourced from Kaggle, contains various features describing houses. The primary objective is to build a model that accurately predicts house prices based on these features.

## Linear Regression

Linear regression is a statistical method that models the relationship between a dependent variable (target) and one or more independent variables (features). It assumes a linear relationship between the input variables and the output, aiming to fit a line that best represents the data.

## Project Description

### Dataset

The dataset used in this project is sourced from Kaggle: [House Sales in King County, USA](https://www.kaggle.com/datasets/shree1992/housedata). It includes the following features:
- **Target variable**: `price` (house price)
- **Numerical features**: `bedrooms`, `bathrooms`, `sqft_living`, `sqft_lot`, `floors`, `sqft_above`, `sqft_basement`, `yr_built`, `yr_renovated`
- **Categorical features**: `waterfront`, `view`, `condition`, `grade`, `zipcode`

### Approach

1. **Data Preprocessing**
   - Handle missing values
   - Drop irrelevant columns (`id`, `date`)
   - Identify and separate numerical and categorical features

2. **Data Splitting**
   - Split the data into training and testing sets

3. **Feature Scaling**
   - Scale numerical features using `StandardScaler`

4. **Feature Encoding**
   - One-hot encode categorical features using `OneHotEncoder`

5. **Model Training**
   - Train a linear regression model on the preprocessed training data

6. **Model Evaluation**
   - Evaluate the model using metrics such as Mean Squared Error (MSE) and R-squared (R2)

7. **Predictions**
   - Make predictions using the trained model
