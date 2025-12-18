# 🌦️ Weather Prediction App

This project focuses on predicting **Land and Ocean Average Temperature** using historical global climate data.  
A machine learning regression model is trained to learn the relationship between land temperatures  
(average, maximum, minimum) and the combined land–ocean temperature.

---

## 📌 Project Overview

- Uses historical global temperature data
- Performs data cleaning and feature engineering
- Trains a regression-based machine learning model
- Evaluates model performance using **Mean Absolute Error (MAE)**

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas**, **NumPy**, **Matplotlib**
- **Scikit-learn**
  - RandomForestRegressor  
  - Pipeline  
  - StandardScaler  
  - Train-Test Split  

---

## 📊 Dataset Description

The dataset contains historical monthly temperature records with features such as:
- Land Average Temperature
- Land Maximum Temperature
- Land Minimum Temperature
- Land and Ocean Average Temperature (Target variable)

Missing values are handled during preprocessing, and the data is indexed by year.

---

## 🤖 Model & Approach

- Features used:
  - LandAverageTemperature
  - LandMaxTemperature
  - LandMinTemperature
- Target:
  - LandAndOceanAverageTemperature
- Model:
  - Random Forest Regressor wrapped inside a Scikit-learn Pipeline
- Data split:
  - 75% Training
  - 25% Testing

---

## 📈 Results

- **Baseline MAE:** ~1.63  
- **Test MAE:** ~0.03  
- **Train MAE:** ~0.004  

The low MAE on test data indicates strong predictive performance and good generalization.

---

## 📁 Project Structure

WEATHER_PREDICTION_APP/
├── README.md
├── weather_data.csv
└── weather_prediction_app.ipynb

---



