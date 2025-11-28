# Medical-device-calibration-software
Calibration and Performance Evaluation of FLIR and ICI Infrared Thermographs Against Reference Oral Temperature in a Clinical Cohort.
## Project Overview

This project evaluates and compares the performance of **FLIR** and **ICI** thermal cameras for clinical fever screening. The goal is to determine which camera provides better accuracy in predicting oral temperatures using machine learning models. The project uses error metrics such as **MAE (Mean Absolute Error)**, **RMSE (Root Mean Squared Error)**, **MAPE (Mean Absolute Percentage Error)**, and **R² (Coefficient of Determination)** to assess the accuracy and reliability of each camera.

## Key Features
- **Data Preprocessing**: Handles missing values and prepares data for analysis.
- **Model Training**: Trains machine learning models using Random Forest Regressor.
- **Error Metrics**: Evaluates model performance using MAE, RMSE, MAPE, and R².
- **Final Comparison**: Compares the performance of FLIR and ICI cameras to determine which one is more accurate.

## Requirements

Before running the project, you need to install the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
