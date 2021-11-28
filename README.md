# INSAID2021-ML-Advanced-Seattle_Weather_Prediction
INSAID 2021 ML Advanced Term Project
# Project Description
## Introduction
Client for this project is a top forecasting company.

They specialize in providing tailored IT solutions for weather forecasting, the energy industry, and the trading market.
They have extensive experience in developing market-leading forecasting systems and high-speed processing solutions for weather data.

They are committed to the creation of accurate weather forecasts that clients can trust, going to extra effort to make their weather API easy to consume.

## Current Scenario
They have created purpose-built weather drones, allowing them to capture observations missed by traditional methods (such as satellites and weather balloons), and calculating forecasts on the fly to ensure a customer receives a forecast based on the latest observations.

## Problem Statement
The current process suffers from the following problems:

* The forecasting process is based on making predictions using a large number of variables, and performing complex calculations on them.
* This results in a massive load on the servers and also causes a slight delay in receiving the forecasts.

They want to make the forecasting process more efficient.

## Project Task
* Datasets containing complete records of daily rainfall patterns of Seattle are provided.
* Project task is to build a classification model using the datasets.
## Project Deliverables
* Deliverable: Predict whether it will rain on a specific day or not.
* Machine Learning Task: Classification
* Target Variable: RAIN
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the Accuracy Score.
# Data Description
* The dataset contains complete records of daily rainfall patterns of Seattle.
* The column RAIN tells us whether rain was observed on a particular day or not.

This is the data that we have to predict for future samples.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 20440 rows and 6 columns.
* The last column RAIN is the target variable.

## Test Set:
* The test set contains 5110 rows and 5 columns.
* The test set doesn’t contain the RAIN column.

It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique identity of each observation. |
|02| **DATE**      | The date of the observation.|
|03| **PRCP**        | The amount of precipitation, in inches.|
|04| **TMAX**          |The maximum temperature for that day, in degrees Fahrenheit.|
|05| **TMIN**      | The minimum temperature for that day, in degrees Fahrenheit |
|06| **RAIN**           | TRUE if rain was observed on that day, FALSE if it was not|
