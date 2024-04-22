# Charan_katta_Finalproj
# Bank Marketing Dataset Analysis

This repository contains code for analyzing the Bank Marketing dataset using various machine learning and deep learning algorithms.

## Overview

The Bank Marketing dataset is used to predict whether a client will subscribe to a term deposit with the bank based on various features such as age, job, marital status, education, etc.

## Data Preprocessing

- The dataset is loaded using Pandas from the CSV file `bank-additional-full.csv`.
- Descriptive statistics of the dataset are displayed using `df.describe()` to gain insights into the data.
- Information about the dataset is printed using `df.info()` to understand the data types and missing values.
- Categorical variables are encoded using Label Encoding for preprocessing.

## Machine Learning Algorithms

The following machine learning algorithms are used for classification:

- Random Forest
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Naive Bayes

Evaluation metrics such as accuracy, precision, recall, and F1-score are calculated using cross-validation.

## Deep Learning

A simple deep learning model is implemented using TensorFlow/Keras:

- A sequential model with dense layers is defined.
- The model is trained using binary cross-entropy loss and Adam optimizer.

## Evaluation Metrics

- Confusion matrix is calculated to evaluate model performance.
- Metrics such as accuracy, precision, recall, and F1-score are computed for each algorithm.
- Average performance metrics across all folds are reported for each algorithm.


## Results

- Performance metrics including accuracy, precision, recall, and F1-score are reported for each algorithm.
- Average metrics across all folds are displayed for comparison.

## Iteration Analysis

- Average performance metrics are reported for each algorithm in each iteration of cross-validation.
- Concatenated dataframes are displayed to show metrics for all algorithms across all iterations.

## About My results
Considering all these metrics, SVM appears to perform the best overall, followed by Deep Learning and then Random Forest. However, the choice of the best classifier can also depend on specific requirements and constraints of the problem domain, as well as considerations regarding computational complexity and interpretability. 

