# Network Traffic Time Series Analysis & Machine Learning

## Overview

This repository documents my hands-on journey of learning Data Analysis, Time Series Analysis, Machine Learning, and Feature Engineering using a large real-world network telemetry dataset.

The goal of this project is not cybersecurity analysis. Instead, I am using this dataset to understand how real-world large-scale data behaves and how machine learning workflows are applied in practice.

## Learning Objectives

Through this project, I am exploring:

* Exploratory Data Analysis (EDA)
* Statistical analysis of real-world datasets
* Time Series Analysis
* Feature Engineering
* Forecasting and Prediction
* Model Evaluation
* Unsupervised Learning
* Anomaly Detection
* Data Visualization
* Model Interpretation

## Dataset

The dataset contains aggregated network traffic telemetry collected over multiple time resolutions:

* 10-minute intervals
* 1-hour intervals
* 1-day intervals

Each subnet is represented as an individual time series and includes metrics such as:

* Number of flows
* Number of packets
* Number of bytes
* Destination IP diversity
* Destination ASN diversity
* Destination port diversity
* TCP/UDP ratios
* Traffic direction ratios
* Average connection duration
* Average TTL

## Topics Being Explored

### Phase 1 — Data Understanding

* Dataset profiling
* Missing value analysis
* Statistical summaries
* Distribution analysis
* Correlation analysis

### Phase 2 — Time Series Foundations

* Trend analysis
* Seasonality analysis
* Stationarity testing
* STL decomposition
* ACF and PACF analysis

### Phase 3 — Feature Engineering

* Lag features
* Rolling statistics
* Time-based features
* Data leakage prevention

### Phase 4 — Forecasting

* Baseline models
* Linear Regression
* Random Forest
* XGBoost
* Forecast evaluation metrics

### Phase 5 — Unsupervised Learning

* PCA
* Clustering
* Behavioral pattern discovery

### Phase 6 — Anomaly Detection

* Statistical methods
* Isolation Forest
* Unusual behavior identification

## Repository Structure

```text
data/
notebooks/
src/
results/
README.md
```

## Current Status

🚧 Work in Progress

This repository is primarily a learning and experimentation space where I document findings, test hypotheses, and build practical machine learning intuition using large-scale time-series data.

## Skills Practiced

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Time Series Analysis
* Machine Learning
* Data Visualization
* Statistical Analysis
* Feature Engineering

## Goal

By the end of this project, I aim to develop a complete end-to-end workflow for analyzing large-scale time-series datasets, engineering meaningful features, training predictive models, and interpreting model behavior using real-world data.
