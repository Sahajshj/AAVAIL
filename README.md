# AAVAIL
AAVAIL Revenue Forecasting and Analytics Solution

Project Overview
This project provides a complete AI workflow solution to forecast revenue for the AAVAIL online retail business. The solution includes data ingestion, exploratory data analysis (EDA), multiple predictive models, evaluation against a baseline, and a fully containerized API for deployment. The system also incorporates logging, unit testing, and performance monitoring.

Features

Data Ingestion & Processing:

Scripts to compile raw JSON data into a unified DataFrame.

Feature engineering for time-series forecasting.

Exploratory Data Analysis (EDA):

Visualizations for revenue, purchases, and streaming activity trends.

Identification of seasonal trends and key business insights.

Modeling:

Baseline model and advanced time-series forecasting model.

Models compared for accuracy and error metrics.

Supports predictions per country and for all countries combined.

Deployment:

Flask API for model inference.

Input validation for predictions.

Unit tests for API, model, and logging.

Dockerized for consistent environment and reproducibility.

Monitoring:

Logging of input data, predictions, runtime, and model version.

Mechanisms in place for performance monitoring and anomaly detection.
