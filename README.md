# Automobile Price Prediction

## Project Overview

This project aims to predict automobile prices based on various vehicle characteristics such as engine size, horsepower, curb weight, fuel type, and other technical specifications. The objective is to build a machine learning model that can accurately estimate car prices and identify the key factors influencing pricing.

## Problem Statement

Car prices are influenced by multiple technical and design-related features. The goal of this project is to analyze these factors and develop a predictive model that helps estimate automobile prices accurately.

## Dataset Information

* Dataset: Automobile Price Prediction Dataset
* Records: 200+ automobile instances
* Features: 25+ vehicle attributes
* Target Variable: Price

## Dataset Source

The dataset used in this project is the **Automobile Imports Database (1985 Auto Imports Dataset)** . The dataset contains information about imported automobiles, including technical specifications, design attributes, and pricing details.

**Source:** https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1017-AutoPricePred.zip

**Dataset Records:** 205 Instances

**Features:** 26 Attributes (including target variable Price)

**Target Variable:** Price

## Project Workflow

### 1. Data Collection

* Loaded the automobile dataset.
* Examined dataset structure and feature information.

### 2. Exploratory Data Analysis (EDA)

* Analyzed numerical and categorical features.
* Identified relationships between vehicle attributes and price.
* Visualized feature distributions and correlations.

### 3. Data Preprocessing

* Handled missing values.
* Encoded categorical variables using One-Hot Encoding.
* Selected relevant features for model building.
* Split data into training and testing sets.

### 4. Model Building

Implemented the following regression models:

* Linear Regression
* Random Forest Regression

### 5. Model Evaluation

Evaluation metrics used:

* R² Score
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

## Results

| Model                    | R² Score | RMSE    |
| ------------------------ | -------- | ------- |
| Linear Regression        | 0.9756   | 1519.87 |
| Random Forest Regression | 0.9560   | 2041.69 |

### Best Model

Linear Regression achieved the highest R² score and lowest prediction error, making it the most suitable model for automobile price prediction.

## Key Insights

* Engine size significantly impacts automobile prices.
* Higher horsepower generally leads to higher vehicle prices.
* Curb weight shows a strong positive relationship with price.
* Fuel efficiency features influence pricing trends.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Challenges Faced

* Handling missing values in multiple features.
* Encoding categorical variables.
* Preventing model overfitting.
* Selecting relevant features for better performance.

## Conclusion

A machine learning model was successfully developed to predict automobile prices using vehicle specifications. Among the evaluated models, Linear Regression delivered the best performance with an R² score of 97.56%, providing reliable price predictions and valuable insights into the factors that influence automobile pricing.
