# Forecast Model

The "Forecast Model" project contains models for sales forecasting, specifically utilizing XGBoost and Polynomial Regression models. These models can forecast both monthly and annual sales data.

## Overview

Sales forecasting is crucial for businesses to make informed decisions regarding inventory, staffing, and financial planning. This project aims to provide accurate sales forecasts using machine learning techniques.

## Models Used

- **XGBoost Model**: XGBoost is a popular gradient boosting algorithm known for its efficiency and accuracy in handling large datasets. In this project, the XGBoost model is employed to predict sales trends based on historical data.

- **Polynomial Regression Model**: Polynomial regression is a form of linear regression in which the relationship between the independent variable and the dependent variable is modeled as an nth degree polynomial. This model is utilized to capture more complex relationships between sales data and predictors.

## Usage

The models in this project can be used to forecast sales data either on a monthly or annual basis. Users can input historical sales data and relevant predictors to generate forecasts.

### Integration with Sales Dashboard Websites

To integrate the forecasting model with sales dashboard websites, a Flask API is utilized. This API provides endpoints for receiving input data and returning the forecasted sales results. Integration instructions are provided below.
