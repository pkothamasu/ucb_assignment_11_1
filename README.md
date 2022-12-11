# Practical Assignment 2: Module 11 - Used Car Price Prediction
Research Question: What drives the price of a car?

## Business Understanding

The CRISP-DM process starts with the understanding of the business problem. The purpose of this assignment is to understand data, visualize carefully, model using various regressor algorithms and evaluate which model would be best for the prediction of used car prices for deployment.  

Imagine for example a used car dealer who needs estimates what the price of a used car could be. The car dealer could be interest in predicting the price of a car based on its attributes. In this project we try to answer to the following 3 business questions:

1. What are the top two best model recommendation for the dealers for predictiong used car price after evaluating different models? <br>
2. Discuss the factors of evaluated scores for car price prediction? <br>
3. What are the suggestions for fine tuning the top best models for car price predictions close to the actual price? <br>

The following table of contents provides the plan for the analysis and spanned across the different sections of CRISP-DM process, Data Understanding, Data Preparation, Modeling, Evaluation and Deployment.

<a id="head"></a>
### Table of Contents 
1. [Import necessary libraries](#1)<br>
2. [Read dataset and first glance](#2)<br>
3. [Data Cleaning](#3)
  - [Outliers](#3.1)
  - [Uncorrelated columns](#3.2)
  - [Filling null values](#3.3)
  - [Remove samples based on common sense](#3.4)
  - [Remove insufficient records](#3.5)<br>
4. [Data Visualization](#4)<br>
5. [Model Preparation](#5)
  - [Encoding categorical features](#5.1)
  - [Normalization](#5.2)
  - [Split training and testing set](#5.3)<br>
6. [Models and tuning](#6)
  - [Linear regression](#6.1)
  - [Lasso regression](#6.2)
  - [Ridge Regression](#6.3)
  - [Ridge Regression using GridSearchCV](#6.4)
  - [K-NearestNeighbor](#6.5)<br>
7. [Evaluate by model comparison using R2 score and RMSE values](#7)<br>

## Deliverables

Analysis file: assignment_11_1_used_car_price_prediction-venkata.ipynb <br>
Assets: 'data' and 'image' folders
