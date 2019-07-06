# Bostone House Price Prediction
This repository contains jupyter notebook for Boston House Price Prediction project. We aim to build model that can predict the price of Boston house. This is achieved by evaluating MSE and R^2 score of various models to choose the best model.

The code in the notebook was executed using python 3.6; the following python libraries were used throughout the project:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- xgboost

## Data Source
Data used is provided by sklearn library of python. Data is also exported in .csv file ('Boston_House_Prices.csv')

## Project Structure
- Import data
- Data cleaning and preparation
- Explorartory Data Analysis
- Model Building and Evaluation

## Conclusion
Following feature are considered for model building after EDA.
- INDUS : proportion of non-retail business acres per town
- RM : average number of rooms per dwelling
- TAX : full-value property-tax rate per $10,000
- PTRATIO : pupil-teacher ratio by town
- LSTAT : % lower status of the population


We have got MSE as 0.15 and r^2 score as 0.87 using random forest regressor for prediction of boston house prices.
