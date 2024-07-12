# Boston-housing-price-prediction-linear-regression

## Project Overview
This project aims to predict house prices in Boston using linear regression techniques. It covers both simple and multiple linear regression models, along with model evaluation metrics such as RMSE and R². The Boston Housing dataset is used for this purpose.

## Project Structure
- **Data**
  - `boston_housing.csv`: The dataset used for this project.
- **Notebooks**
  - `01_Data_Preparation.ipynb`: Data loading, cleaning, and preparation.
  - `02_Simple_Linear_Regression.ipynb`: Building and evaluating a simple linear regression model.
  - `03_Multiple_Linear_Regression.ipynb`: Building and evaluating a multiple linear regression model.

## Libraries Required
- pandas
- seaborn
- sklearn
- joblib
- matplotlib
- numpy

## Notebooks Description

### 01_Data_Preparation.ipynb
- Load the Boston Housing dataset.
- Perform initial data exploration.
- Clean the data and handle any missing values.
- Split the data into features (X) and target (y).

### 02_Simple_Linear_Regression.ipynb
- Select a single feature for the simple linear regression model.
- Split the data into training and testing sets.
- Train the simple linear regression model.
- Predict house prices and evaluate the model using R².
- Visualize the regression line.

### 03_Multiple_Linear_Regression.ipynb
- Use all features for the multiple linear regression model.
- Split the data into training and testing sets.
- Train the multiple linear regression model.
- Predict house prices and evaluate the model using RMSE and R².