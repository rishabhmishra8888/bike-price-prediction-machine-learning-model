# bike-price-prediction-machine-learning-model
# Machine Learning Model for Used Bike Price Prediction using K-Nearest Neighbors (KNN) Algorithm

This repository contains a machine learning model based on the K-Nearest Neighbors (KNN) algorithm for predicting the prices of used bikes. The model takes key features such as power, owner age, and kilometers driven as input and provides the final price of the bike as output. The goal of this project is to accurately predict the prices of used bikes to assist buyers and sellers in making informed decisions.

## Table of Contents

- [Introduction](#introduction)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Feature Selection](#feature-selection)
- [Label Encoding](#label-encoding)
- [Correlation Analysis](#correlation-analysis)
- [K-Folds Cross Validation](#k-folds-cross-validation)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Predicting the price of used bikes is a valuable application of machine learning. This project utilizes the KNN algorithm to predict bike prices based on important features such as power, owner age, and kilometers driven.

## Exploratory Data Analysis (EDA)

EDA was performed on the dataset to gain insights into the distribution and characteristics of the data. This step involved data visualization and statistical analysis to identify any trends or patterns.

## Feature Selection

Key features were selected for the model, including power, owner age, and kilometers driven. Careful consideration was given to features that have a significant impact on bike prices.

## Label Encoding

Categorical variables were transformed using label encoding to convert them into a numerical format that can be fed into the machine learning algorithm.

## Correlation Analysis

Pearson correlation analysis was conducted to measure the strength and direction of the linear relationship between input features and the output variable (bike price). This helped in understanding which features have the most influence on the target variable.

## K-Folds Cross Validation

K-Folds cross-validation was employed to assess the model's performance. The dataset was divided into K subsets, and the model was trained and validated K times, using a different subset as the validation set each time. This technique helped in achieving a more accurate assessment of the model's performance.

## Results

The initial model using simple linear regression achieved an accuracy of 65%. However, after implementing the KNN algorithm and applying K-Folds cross-validation, the accuracy of the model improved significantly to 93%. This demonstrates the effectiveness of the KNN algorithm for this prediction task.

## Conclusion

In this project, a machine learning model based on the K-Nearest Neighbors algorithm was developed for predicting used bike prices. Through rigorous exploratory data analysis, feature selection, label encoding, correlation analysis, and K-Folds cross-validation, the model's accuracy was enhanced from 65% to an impressive 93%. This model provides a valuable tool for estimating the prices of used bikes, aiding both buyers and sellers in making well-informed decisions.

Feel free to explore the code and documentation in this repository to gain a deeper understanding of the implementation details and the steps taken to achieve these results.
