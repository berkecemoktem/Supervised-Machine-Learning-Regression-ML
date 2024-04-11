# Red Wine Quality Prediction - Using Regression Techniques

![wine](https://github.com/berkecemoktem/Supervised-Machine-Learning-Regression-ML/assets/75270752/e9e13d75-3ffc-4052-964d-012a04ec4325)


## Introduction
This project aims to predict the quality of red wine based on various chemical properties. The dataset used in this project contains information about different attributes of red wines, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality.

## Dataset
The dataset used in this project is sourced from UCI Machine Learning Repository. It consists of 1599 instances and 12 attributes, including 11 input variables and 1 target variable (quality). Each instance represents a red wine sample, and the quality is rated on a scale from 3 to 8.

## Exploratory Data Analysis
Before diving into modeling, I conducted extensive exploratory data analysis to gain insights into the dataset. Key steps in EDA included:

* Visualization of feature distributions and correlations.
* Identification of potential outliers and missing values.
* Examination of relationships between input features and target variable.

## Techniques Used
In this project, I employed various regression techniques to predict wine quality:

* Linear Regression
* Polynomial Regression
* Ridge Regression
* ElasticNet Regression

## Insights and Key Findings
* Initial data exploration revealed moderate correlations between some input features and wine quality.
* Preprocessing steps included feature selection based on correlation analysis and dropping irrelevant features.
* Despite efforts to improve predictive performance, regression models yielded suboptimal results, with R-squared scores below 0.50.
* __Classification techniques__ such as __K-Nearest Neighbors (KNN), Decision Trees, and Random Forests__ may offer better predictive accuracy and should be explored further
* It would give much better accuracy to use __Multiple Regression__, however, I wanted to stick with the techniques stated above.

## Requirements
* Python 3.x
* Jupyter Notebook
* pandas
* numpy
* scikit-learn
* seaborn
* matplotlib

## Usage
Clone the repository to your local machine:

``` git clone https://github.com/berkecemoktem/wine-quality-prediction.git ```


