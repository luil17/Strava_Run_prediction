# Strava_Run_prediction
Predicting race finish times from personal running history using Strava data and machine learning.

The Problem
This project uses my historical training data to predict how long it will take to finish a race.

Dataset

Personal data exported from the Strava app
Started with 105 features, reduced to the most important features for predicting finish time
207 rows (one per run activity)
Tabular data — most time-based columns are in seconds


Preprocessing

Dropped unnecessary and redundant columns
Filled missing values with column averages (<15 missing values total)
Normalized features to handle outliers
Engineered new features where helpful
Selected most important features using correlation analysis and feature importance
Split: 80% train 20% test


Models
ModelPurposeLinear RegressionBaselineRidge RegressionReduce overfittingRandom ForestCapture nonlinear patterns
Evaluated using RMSE (Root Mean Squared Error).

Goal
Give me a predicted finish time based on my training history.
