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
