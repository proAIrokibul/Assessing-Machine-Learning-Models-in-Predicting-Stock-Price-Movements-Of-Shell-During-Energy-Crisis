# Assessing-Machine-Learning-Models-in-Predicting-Stock-Price-Movements-Of-Shell-During-Energy-Crisis
## Overview

This project provides a comprehensive analysis and classification model for Shell's stock price data. The dataset includes key stock market features such as Open, High, Low, Close, and Volume, among others, and is enriched with insightful data visualizations and preprocessing steps to enable meaningful predictions.

The project focuses on transforming raw stock data into actionable insights and predictive capabilities, enabling business decision-makers to assess stock behavior and trends effectively.

## Features of the Repository

1. **Data Preprocessing**:
   - Converts raw stock data into a clean and structured format.
   - Handles missing values and performs necessary transformations for modeling.

2. **Exploratory Data Analysis (EDA)**:
   - Detailed time-series analysis to track trends and patterns in stock prices.
   - Visualization of statistical properties such as distribution and correlation.
   - Moving averages and seasonality analysis to identify key insights.

3. **Classification Models**:
   - Conversion of the stock price problem into a classification problem.
   - Implementation of multiple models (Logistic Regression, Random Forest, and Support Vector Classifier).
   - Evaluation and comparison of model performance with accuracy metrics and detailed classification reports.

4. **Visualizations**:
   - Professional plots to uncover trends, patterns, and anomalies.
   - Heatmaps, pair plots, lag plots, and autocorrelation plots for deeper insights.

## Results

### Logistic Regression
- **Classification Report**:
  ```
                precision    recall  f1-score   support
             0       0.38      0.20      0.26        87
             1       0.52      0.73      0.61       105

      accuracy                           0.49       192
     macro avg       0.45      0.46      0.43       192
  weighted avg       0.46      0.49      0.45       192
  ```
- **Accuracy**: 49%

### Random Forest
- **Classification Report**:
  ```
                precision    recall  f1-score   support
             0       0.47      0.90      0.62        87
             1       0.65      0.16      0.26       105

      accuracy                           0.49       192
     macro avg       0.56      0.53      0.44       192
  weighted avg       0.57      0.49      0.42       192
  ```
- **Accuracy**: 49%

### Support Vector Classifier
- **Classification Report**:
  ```
                precision    recall  f1-score   support
             0       0.51      0.69      0.59        87
             1       0.64      0.45      0.53       105

      accuracy                           0.56       192
     macro avg       0.57      0.57      0.56       192
  weighted avg       0.58      0.56      0.55       192
  ```
- **Accuracy**: 56%

## Business Insights

- **Trend Identification**: Track historical stock price behavior to inform future investment decisions.
- **Volatility Analysis**: Understand daily price changes to assess risk and market dynamics.
- **Correlation Analysis**: Explore relationships between trading volume and price movement to predict market behavior.
- **Seasonality Insights**: Identify monthly and yearly patterns to align trading strategies with historical performance.
- **Modeling Impact**: Enable classification-based decision-making to forecast stock performance within defined categories, enhancing portfolio management strategies.


