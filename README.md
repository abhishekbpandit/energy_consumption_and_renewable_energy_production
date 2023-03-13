# Energy Consumption and Renewable Energy Production Prediction

This project aims to predict energy consumption and renewable energy production using various machine learning models. The dataset used in this project contains hourly energy consumption and renewable energy production data for a region.

Dataset

The dataset used in this project has been compiled from multiple sources that include energy consumption and sales, weather data, energy production by various sources and various macroeconomic factors.. The dataset contains monthly energy consumption and renewable energy production data for a US over a period from 1994-2017. 

Models

This project uses the following machine learning models:

Support Vector Machine (SVM)
Decision Tree
Random Forest
Generalized Linear Model (GLM) with Tweedie Distribution
Random Forest for Regression

Energy Consumption Prediction
The SVM, Decision Tree, and Random Forest models are used to predict energy consumption. The models are trained using the past energy consumption data and evaluated using the test data. Random Forest had the least RMSE amongst the specified models on the an energy consumption variable obtained by using the first component of PCA fit on the multi-collinear energy consumption variables.

Renewable Energy Production Prediction
The GLM with Tweedie Distribution and Random Forest for Regression models are used to predict renewable energy production. The models are trained using the past renewable energy production data and evaluated using the test data. T

Requirements

To run this project, you will need the following software:

Python 3
Pandas
Matplotlib
Seaborn
Scikit-learn
StatsModels
XGBoost
