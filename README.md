# House_Price_Prediction

## Project Objective

This project aims to predict house prices in Boston based on multiple factors such as the number of rooms, student-teacher ratio, crime rate, and other socio-economic variables. By leveraging machine learning models, we aim to provide an accurate estimation of housing prices, which can assist buyers, sellers, and real estate investors in making informed decisions.

## Problem Statement

The real estate market is influenced by various economic and demographic factors, making it challenging to determine property prices accurately. Key issues include:

Lack of transparency in price determination.

Overvaluation or undervaluation of properties due to market fluctuations.

Difficulty for buyers and investors in assessing fair market prices.

By using machine learning regression models, this project helps:

Identify key factors that affect housing prices.

Provide a data-driven price prediction approach.

Assist stakeholders in making better investment decisions.

## Background

The Boston Housing Dataset is widely used in predictive analytics. It contains 14 features and 506 entries, including variables like:

Crime rate in the neighborhood.

Number of rooms per dwelling.

Proportion of non-retail business acres.

Student-teacher ratio.

Accurately predicting house prices is crucial for real estate developers, investors, and policy-makers to ensure better urban planning and investment strategies.

## Project Output

Exploratory Data Analysis (EDA) to understand data trends.

Feature selection to identify key factors affecting house prices.

A machine learning regression model to predict house prices.

Performance evaluation using regression metrics like MAE, RMSE, and R².

## Methodology

Exploratory Data Analysis (EDA):

Data visualization using matplotlib and seaborn.

Identifying correlations between variables and housing prices.

Data Preprocessing:

Setup data, such as bining feature, etc.

Machine Learning Modeling:

CatBoost Regressor → Chosen because it provides better results compared to other models.

Comparison with other regression models.

Model evaluation using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.

Final Predictions:

Using the trained model to predict house prices based on given features.

## Tech Stack

Programming Language: Python

Libraries:

PyCaret → For automated machine learning and model selection.

Pandas → For data manipulation.

Matplotlib & Seaborn → For data visualization.

CatBoost Regressor → For predictive modeling.

Environment: Jupyter Notebook

## Project Files

house_price.ipynb = Jupyter Notebook containing the entire analysis, modeling, and prediction process

logs = installation process

catboost_info (folder) = modelling process


