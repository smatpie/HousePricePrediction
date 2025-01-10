# House Price Prediction Model

Hey, this repo contains a machine learning model to predict house prices based on various features like square footage, number of bedrooms, bathrooms, neighborhood, and year built. The model was built using **Random Forest Regressor** algorithm, and the dataset used is publicly available.

You can change the dataset as you wish, do adjust the features for that though. I was able to achieve 99.9999% accuracy with this model.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model](#model)

  
## Project Overview

This project uses a **Random Forest Regressor** to predict house prices. The dataset is preprocessed to handle missing values, encode categorical features, and split the data into training and testing sets.

## Dataset

The dataset used in this project is from Kaggle and can be found [here](https://www.kaggle.com/datasets/muhammadbinimran/housing-price-prediction-data).

The dataset contains the following columns:
- `SquareFeet`: The area of the house in square feet.
- `Bedrooms`: The number of bedrooms.
- `Bathrooms`: The number of bathrooms.
- `Neighborhood`: The neighborhood the house is located in.
- `YearBuilt`: The year the house was built.
- `Price`: The target variable, which is the price of the house.

## Model

The model uses the **Random Forest Regressor** from `scikit-learn`. The key steps involved are:
1. Data preprocessing: Handle missing values and encode categorical variables.
2. Model training: Train a Random Forest model using the training data.
3. Model evaluation: Evaluate the model using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.

