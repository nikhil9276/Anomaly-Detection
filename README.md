                                                          Anomaly Detection in Time Series Data
This repository contains code for detecting anomalies in time series data using Python. The project includes components for data preparation, visualization, exploratory data analysis (EDA), and anomaly detection using a Random Forest classifier.

Project Overview
Anomaly detection in time series data is essential for identifying unusual patterns that could signify important events or errors. This project uses machine learning techniques to improve the accuracy and interpretability of anomaly detection.

Components
1. Data Preparation
Reading Data: Load time series data and anomaly labels from CSV files.
Handling Missing Values: Manage any missing values to ensure data integrity.
Merging Data: Combine time series data with anomaly labels.
2. Visualization
Plotting: Create plots of the time series data.
Highlighting Anomalies: Mark anomalies on the plots.
3. Exploratory Data Analysis (EDA)
Statistical Summary: Compute summary statistics of the data.
Distribution Plots: Visualize the distribution of values and anomalies.
4. Anomaly Detection
Feature Engineering: Create new features from the data.
Model Training: Train a Random Forest classifier.
Model Evaluation: Assess model performance with accuracy scores and confusion matrices.
Feature Importance: Analyze important features contributing to anomalies.
Summary Log
Results and outputs are logged for record-keeping and analysis.

Getting Started
Prerequisites
Python 3.x
pandas, numpy, matplotlib, seaborn, scikit-learn, keras (if using a pre-trained model)
