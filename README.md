# Big Data: Spark Traffic Analysis and Keras Transfer Learning Project

## Railway Traffic Prediction using Spark

This project analyzes public transportation traffic patterns in the Île-de-France region (Paris metropolitan area) using Apache Spark to process ticket validation data. The analysis focuses on ticket categories, traffic fluctuations, and the impact of COVID-19 lockdowns. Additionally, the project implements a 7-day traffic prediction model.

## Project Objectives

1. **Data Collection**: Retrieve and process daily validation data from the Île-de-France Mobility Open Data portal
2. **Exploratory Data Analysis**: Analyze historical data from 2019 to 2021
3. **Data Processing**: Clean and prepare data for predictive modeling
4. **Traffic Forecasting**: Develop models to predict passenger flow

## Technical Requirements

- Python 3.7 or higher
- Apache Spark (PySpark)
- Development Environment Options:
  - Google Colab (recommended for easy setup)
  - Local installation with required dependencies
- Internet connection for data downloads
- Sufficient storage space for large datasets

## Data Analysis Pipeline

### Initial Data Exploration
- Column identification and data type analysis
- Missing value detection and anomaly identification
- Data quality assessment and validation

### Historical Data Construction
- Merging semester-based datasets into a unified timeline
- Data normalization and standardization
- Temporal alignment of different data sources

### Statistical Analysis
- Calculation of key metrics:
  - Daily, weekly, and monthly passenger volumes
  - Peak hour patterns
  - Seasonal trends
  - Impact analysis of special events and lockdowns

## Model Development
- Time series analysis
- Feature engineering for prediction
- Implementation of forecasting models
- Model validation and performance metrics
