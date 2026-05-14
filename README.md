# DVD Rental Regression

Machine learning regression project predicting the number of days customers rent DVDs using structured rental data.

## Project Overview

This project uses regression models to predict DVD rental duration based on customer transactions, movie characteristics, rental pricing, and special features.

The goal is to build a regression model achieving a Mean Squared Error (MSE) below 3 on the test dataset.

## Dataset Notice

The original dataset (`rental_info.csv`) was provided through a DataCamp educational project and is not included in this repository.

## Dataset Features

The dataset includes:

- rental_date
- return_date
- amount
- amount_2
- rental_rate
- rental_rate_2
- release_year
- length
- length_2
- replacement_cost
- special_features
- movie rating dummy variables

## Feature Engineering

Additional preprocessing steps include:

- Converting rental and return dates into datetime format
- Creating rental_length_days target variable
- Creating dummy variables:
  - deleted_scenes
  - behind_the_scenes

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn

## Machine Learning Model

Model used:

- RandomForestRegressor

## Project Goal

Predict the number of days a customer rents a DVD while minimizing prediction error and improving inventory planning efficiency.

## Repository Structure

dvd-rental-regression/
│
├── rental_regression.ipynb
├── rental_regression.py
├── README.md
├── requirements.txt

## Author

Lydia L
