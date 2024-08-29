# Delivery Time Prediction Using Random Forest

This repository contains the implementation of a predictive model for estimating delivery times in an online food delivery service. The project uses the Random Forest algorithm due to its robustness in handling complex datasets and resistance to overfitting.

## Project Overview
The goal of this project is to enhance operational efficiency and improve customer satisfaction by providing accurate delivery time predictions. The Random Forest model integrates various factors such as delivery personnel ratings, distance, and type of orders to generate reliable forecasts.

## Key Features
- **Data Preprocessing**: Includes steps like anomaly correction, outlier detection, and feature engineering to prepare the dataset for model training.
- **Exploratory Data Analysis (EDA)**: Provides insights into the key variables influencing delivery times.
- **Model Training and Optimization**: The Random Forest model is trained on 80% of the data and optimized using grid search and cross-validation techniques to improve accuracy.
- **Feature Importance Analysis**: Identifies the most significant factors affecting delivery times, with delivery personnel ratings and distance being the top predictors.

## Results
The optimized model achieved a Mean Absolute Error (MAE) of 5.98 and a Root Mean Square Error (RMSE) of 7.66, indicating a high level of accuracy in predicting delivery times.

## Business Value
Implementing this model in a real-world online food delivery service can lead to:
- **Improved Delivery Efficiency**: Optimized routes and schedules reduce costs and increase speed.
- **Enhanced Customer Satisfaction**: Accurate delivery time predictions improve customer trust and satisfaction.
- **Cost Reduction**: Efficient resource management leads to lower operational costs.
- **Strategic Decision Making**: Insights from the model support better business strategies and targeted marketing.

## Future Work
Future improvements could include integrating real-time traffic and weather data to further enhance the accuracy of delivery time predictions and developing a user-friendly interface for real-time order tracking.

