Air Quality Forecasting using LSTM

Overview

In this project, I built a deep learning model using Long Short-Term Memory (LSTM) networks to forecast air pollution levels (PM2.5). The goal is to understand how past environmental conditions influence future pollution levels and to demonstrate how time-series models can be used for forecasting.

---

Dataset

The dataset contains historical air quality and weather-related measurements, including:

- PM2.5 (target variable)
- Temperature (TEMP)
- Dew Point (DEWP)
- Atmospheric Pressure (PRES)

These variables are recorded over time, making the dataset suitable for time-series forecasting.

---

Problem

This is a regression problem where the objective is to predict future PM2.5 values based on past observations.

---

What I did

Data preprocessing

- Selected relevant environmental features
- Removed missing values
- Normalized the data using MinMaxScaler

---

Sequence creation

- Converted data into time-series sequences
- Used past time steps to predict future PM2.5 values

---

Model

I built a Long Short-Term Memory (LSTM) model using TensorFlow/Keras:

- LSTM layer to capture temporal dependencies
- Dense output layer for prediction

Why LSTM?

LSTM networks are designed to handle sequential data and can remember patterns over time, making them ideal for forecasting tasks.

---

Training

- Optimizer: Adam
- Loss function: Mean Squared Error (MSE)
- Trained over multiple epochs with validation split

---

Results

The model was able to learn patterns from historical data and produce reasonable predictions of PM2.5 levels.

---

📊 Visualization

Actual vs Predicted PM2.5

"Prediction" (prediction_plot.png)

---

Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

Why this project matters

Air pollution forecasting is important for environmental monitoring and public health. This project demonstrates how deep learning models like LSTM can be used to analyze and predict time-dependent environmental data.

---

Future Improvements

- Use larger and more diverse datasets
- Add more environmental variables
- Tune hyperparameters for better performance
- Compare with other time-series models

---

About me

-Dr Divya Pragna MULLA
About me

I am building practical skills in machine learning and deep learning by working on real-world datasets, especially in environmental and data-driven applications.
