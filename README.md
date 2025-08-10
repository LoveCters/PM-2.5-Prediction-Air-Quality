# Air Quality Prediction (PM2.5) with LSTM

## Overview

This project focuses on predicting **PM2.5 air pollution levels** using a Long Short-Term Memory (LSTM) deep learning model. The model leverages historical air quality data, preprocesses it into a time-series format, and predicts future PM2.5 concentrations.
The prediction system is designed for **Ho Chi Minh City**, but can be adapted to other locations with appropriate datasets.

## Project Structure

* **ModelPredictPM2.5.ipynb**
  Contains the full workflow:

  * Data preprocessing and cleaning
  * Time-series sequence generation
  * LSTM model building and training
  * Model evaluation using multiple metrics
  * Visualization of predictions vs. actual values

* **UserChoice.ipynb**
  A lightweight notebook allowing users to:

  * Load the trained LSTM model
  * Input custom parameters or time ranges
  * Generate and display PM2.5 predictions interactively

## Main Features

* **Data Preprocessing**: Missing value handling, normalization, and supervised learning format generation.
* **Time-Series Modeling**: LSTM architecture for sequential data prediction.
* **Model Optimization**: Early stopping, learning rate scheduling, and model checkpointing.
* **Evaluation Metrics**: RMSE, MAE, and R² score for performance assessment.
* **User-Friendly Prediction**: Simple interface for generating future PM2.5 forecasts without retraining.

## Technologies Used

* **Deep Learning**: TensorFlow, Keras (LSTM, Dropout, Dense layers)
* **Data Processing**: Pandas, NumPy, Scikit-learn
* **Visualization**: Matplotlib, Seaborn
* **Optimization**: EarlyStopping, ReduceLROnPlateau, ModelCheckpoint, Adam Optimizer
