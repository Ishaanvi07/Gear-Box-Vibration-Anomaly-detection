# Gear-Box-Vibration-Anomaly-detection
# NTM Vibration Anomaly Detection

## Overview

An unsupervised machine learning project to identify abnormal vibration patterns in a rolling mill process using machine operating parameters.

## Problem Statement

Unexpected vibration behavior in industrial equipment can indicate abnormal operating conditions.
This project analyzes vibration data and detects unusual patterns using anomaly detection techniques.

## Dataset Features

The dataset contains industrial process parameters such as:

- RPM
- Entry Vibration
- Exit Vibration
- NTM Stand
- Line information
- Size parameters

## Workflow

1. Data loading and exploration
2. Data cleaning and missing value handling
3. Exploratory Data Analysis
4. Feature engineering
5. Anomaly detection
6. Visualization of abnormal operating conditions

## Machine Learning Approach

Isolation Forest was used for unsupervised anomaly detection.

## Features Created

- RPM-normalized vibration feature
- Encoded line information

## Results

The model identifies abnormal vibration patterns which can help in early detection of unusual machine behavior.

## Future Improvements

- Integrate real-time sensor streaming
- Build monitoring dashboard
- Combine anomaly detection with predictive maintenance models
