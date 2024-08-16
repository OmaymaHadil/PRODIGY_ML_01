# PRODIGY_ML_01
# House Price Prediction using Linear Regression

## Overview
This project implements a **Linear Regression model** to predict house prices based on various features such as square footage, number of bedrooms, and number of bathrooms. The dataset used for this project is provided by Kaggle and is part of the "House Prices: Advanced Regression Techniques" competition.

## Dataset
The dataset used for this project can be found on Kaggle:
- [House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

### Files in the Dataset
- `house_price_prediction.ipynb`: The Jupyter Notebook containing the code for data exploration, model building, and evaluation
- `train.csv`: The training set used to build the model.
- `test.csv`: The test set used for predictions.
- `README.md`: This file, providing an overview and instructions.

### Data Fields
Here’s a brief overview of some key fields in the dataset:
- **SalePrice**: The property's sale price in dollars. This is the target variable.
- **MSSubClass**: The building class.
- **MSZoning**: The general zoning classification.
- **LotFrontage**: Linear feet of street connected to the property.
- **LotArea**: Lot size in square feet.
- And many more...

## Model
The model is a simple Linear Regression that takes into account the following features:
- Square footage (LotArea, GrLivArea)
- Number of bedrooms (Bedroom)
- Number of bathrooms (FullBath, HalfBath)

## Requirements
To run the project, you'll need the following Python packages:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
