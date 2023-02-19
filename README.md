# Rain-Fall-Prediction-Aquib

Rainfall Prediction Model Report
Introduction
The purpose of this report is to present a model for predicting daily rainfall using open meteo
data. The model was trained on a dataset consisting of daily weather data from 2019-01-14 to
2022-01-14. The model's performance was evaluated using mean squared error, R2 score, and
accuracy. This report also provides information on the model architecture and conclusions on
the model's performance.
Input Features
The model uses the following features as input:
● time
● weathercode (wmo code)
● temperature_2m_mean (°C)
● apparent_temperature_max (°C)
● rain_sum (mm)
● precipitation_hours (h)
● windspeed_10m_max (km/h)
● windgusts_10m_max (km/h)
● winddirection_10m_dominant (°)
● et0_fao_evapotranspiration (mm)
● Model Performance

Two models were evaluated on the held-out test set using the following metrics:
Linear Regression Model
Mean Absolute Error (MAE): 9.191
R2 Score : 0.60
Adjusted R2 Score: 0.59
XGBoost Regressor Model
Mean Absolute Error (MAE): 0.173
R2 Score: 0.95


A best model was a XgBoost Regression with R2-Score of 0.95.
