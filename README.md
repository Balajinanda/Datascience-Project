# Datascience-Project
## Project Title : Human Activity Recognisition Using Smart Phones

## Project Description  
This project focuses on Human Activity Recognition (HAR) using data collected from wearable and environmental sensors. The objective is to classify various physical activities performed by individuals, such as walking, running, sitting, and more, based on sensor data. The PAMAP2 dataset is used as the primary data source, and deep learning models have been implemented and compared for accurate activity classification.

![image](https://github.com/user-attachments/assets/7ec1cb98-f0f8-4667-9fba-44d003e73af9)

## Table Of Contents
1. Introduction
2. Dataset Description
3. Methodology
4. Results
5. Applications
6. Future Work
7. References

   

## 1.Introduction
Human Activity Recognition (HAR) is a rapidly growing field with applications in healthcare, fitness tracking, smart homes, and workplace safety. By analyzing data from wearable sensors, HAR systems classify activities such as walking, running, and cycling. This project evaluates and optimizes several machine learning models to identify the best-performing architecture for HAR tasks.



## 2.Dataset Description

Source: PAMAP2 Physical Activity Monitoring dataset from the UCI Machine Learning Repository.

Data Collection: Data was gathered from wearable sensors (IMUs and heart rate monitors) placed on participants' hands, chest, and ankles. Activities included daily tasks like ironing, sitting, and walking.

Features: Timestamp, activity ID, heart rate, and sensor readings (acceleration, gyroscope, magnetometer).

Preprocessing: Missing values were imputed, features normalized, and data segmented into fixed-size windows for time-series analysis.



## 3.Methodology

Models Implemented:

CNN: Captures spatial dependencies in sensor data.

ANN and MLP: Baseline models for feature classification.

RNN: Leverages sequential data relationships.

LSTM: Advanced RNN variants for long-term dependencies.

CNN-LSTM Hybrid: Combines spatial and temporal feature extraction.

Key Steps:

Data preprocessing: Filling missing values, normalizing data, and segmenting it for sequential models.

Model training: Optimized each model for HAR tasks using appropriate architectures and loss functions.

Evaluation metrics: Accuracy, precision, recall, F1-score, and confusion matrices were used to assess performance.

Hyperparameter tuning: Fine-tuned parameters such as layer units, dropout rates, and optimizers for LSTM and CNN-LSTM models.



## 4.Results

Best Models:

LSTM:

Accuracy: 94%

Strength: Combines CNN's spatial analysis with LSTM's temporal modeling.

CNN-LSTM Hybrid:

Accuracy: 89%

Strength: Combines CNN's spatial analysis with LSTM's temporal modeling.

Key Findings:

Hybrid models outperformed standalone architectures, highlighting the importance of combining spatial and temporal analysis.

ANN and MLP models underperformed, showing limitations in capturing complex temporal patterns.

Visualization:

Detailed plots comparing accuracy, precision, recall, and F1-score for all models.

Confusion matrices for analyzing model-specific misclassifications.



## 5.Applications

Healthcare: Monitoring patient mobility, detecting falls, and assisting in rehabilitation.

Fitness Tracking: Providing detailed insights into exercise routines.

Smart Homes: Enabling context-aware automation based on activity recognition.

Industrial Safety: Ensuring compliance with safety protocols through activity monitoring.



## 6.Future Work

Dataset Augmentation: Include real-world, noisy data to improve generalization.

Model Optimization: Explore lightweight models (e.g., MobileNet) for edge deployment.

Multimodal Analysis: Combine wearable sensor data with audio or video inputs for richer context.
