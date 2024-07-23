# Project Name: California Housing Market Analysis and Forecast

### Project Status: Complete

## Project Intro/Objective
The purpose of this project is to analyze the housing market trends in various cities in California, including Fresno, Sacramento, San Diego, San Francisco, San Luis Obispo, Los Angeles, Riverside, and Merced. By utilizing data obtained through the Zillow API and the Federal Reserve Bank of St.Louis. By implementing an XgBoost machine learning model, I aim to forecast future housing prices and provide valuable insights into the market. This project mainly aims to assist potential future home owners and those in real estate into the potential future for the housing market.

## Methods Used
- Data Cleaning 
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning
- Data Visualization
- Predictive Modeling

## Technologies
- Python
- Pandas
- Jupyter
- Darts Python Library
- Tableau

## Project Description
This project focuses on the analysis of housing market data from eight major cities in California. The data was sourced from the Zillow API and FRED, which provides comprehensive real estate and consumer price index (CPI) data. Our primary objective is to create a reliable time series forecasting model using XgBoost to predict future housing prices. 

Key questions and hypotheses include:
- How do housing prices vary across different cities in California?
- What are the trends and patterns in the housing market over time?
- Can we accurately forecast future housing prices using machine learning models?

Challenges faced:
- Handling and preprocessing large datasets
- Ensuring the accuracy and reliability of the forecasting model

## Links to each step of the process
- Data Preprocessing (https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/Preprocessing.ipynb)
- Exploratory Data Analysis (EDA) (https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/EDA.ipynb)
- Model Creation and Predictions (https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/Housing_model.ipynb)
- Tableau workbook (https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/Cali_Housing_Workbook.twb)

## Additional notes
Overall the forecasting for median prices turned out very well, however predicting future average home values led to extreme undershooting of predicted values for unknown reasons. I decided to exclude the predicted home values because of this and only include the forecasted median prices. Also, due to issues with Tableau licensing, I was unable to publish my dashboard. However screenshots of it's
entirety are provided below

## Bar charts and Analytics Summary:
![alt text](https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/Assets/KPI%20and%20Bar%20Charts.png "KPI")

## Line Graphs with median home price forecast:
![alt text](https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/Assets/Line_Graphs.png "Line Graphs")

## Median Geo Map:
![alt text](https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/Assets/Median%20Geo%20Map.png "Geo Map 1")

## Value Geo Map:
![alt text](https://github.com/AlbertHender/Cali_Housing_forecast/blob/main/Assets/Value%20Geo%20Map.png "Geo Map 2")

## Contact
-Email: adhender@ucsd.edu

