# ECG Anomaly Detection

This project focuses on detecting anomalies in Electrocardiogram (ECG) data. The analysis involves processing ECG signals and identifying abnormalities using statistical methods and time series modeling.

## Introduction

Electrocardiography (ECG) is a vital tool in diagnosing cardiac abnormalities by recording the electrical activity of the heart over time. Anomalies in ECG signals can indicate various cardiac conditions, making their detection crucial for early diagnosis and intervention. This project aims to develop techniques for automatic detection of anomalies in ECG data.

## Dataset

The dataset used in this project consists of ECG signals collected from patients. It contains multiple leads representing different perspectives of cardiac activity. Each lead corresponds to a specific electrode placement on the body.

## Analysis

The analysis is conducted using Python and various libraries such as Pandas, Matplotlib, NumPy, and Statsmodels. The major steps of the analysis include:

1. Data Preprocessing: Loading the ECG data, handling missing values, and preparing the dataset for analysis.

2. Visualization: Plotting ECG signals for different leads to visualize the cardiac activity over time.

3. Stationarity Test: Performing Augmented Dickey-Fuller (ADF) test to check the stationarity of the ECG signals.

4. Anomaly Detection: Implementing anomaly detection algorithms such as Z-Score method and ARIMA (AutoRegressive Integrated Moving Average) model to identify abnormal patterns in the ECG signals.

## Results

The analysis successfully detects anomalies in the ECG signals, indicating potential cardiac abnormalities. Visualizations and statistical tests provide insights into the nature and severity of these anomalies, aiding in further medical evaluation and treatment.

## Conclusion

Automatic detection of anomalies in ECG signals is crucial for timely diagnosis and intervention in cardiac patients. This project demonstrates the effectiveness of statistical methods and time series modeling in identifying abnormal patterns in ECG data, laying the foundation for future research in cardiac health monitoring and diagnosis.
