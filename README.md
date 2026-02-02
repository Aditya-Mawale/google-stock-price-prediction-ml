# google-stock-price-prediction-ml
📈 Google Stock Price Prediction using LSTM
This project focuses on analyzing and predicting Google (GOOG) stock prices using historical market data and a Long Short-Term Memory (LSTM) deep learning model. The goal is to understand long-term price trends and forecast future closing prices using time-series analysis.

🔍 Project Overview
Historical stock data is fetched using Yahoo Finance (yfinance)
Exploratory Data Analysis (EDA) is performed to understand trends and patterns
Technical indicators like moving averages and percentage change are calculated
Data is scaled and prepared for time-series modeling
An LSTM neural network is trained to predict future stock prices
Model performance is evaluated and visualized
The trained model is saved for future use

Key Features
📊 20 years of Google stock data analysis
📈 Interactive trend visualization using Matplotlib
🔄 100-day & 250-day moving averages
📉 Percentage change analysis of closing prices
🧠 LSTM-based deep learning model for prediction
⚙️ MinMaxScaler normalization for better training
📐 Train–test split (70% / 30%)
📉 RMSE calculation for model evaluation
💾 Saved trained model (.keras) for reuse

Tech Stack
Python
yfinance
Pandas & NumPy
Matplotlib
Scikit-learn
TensorFlow / Keras
Google Colab

Workflow
Fetch Google stock data using yfinance
Perform exploratory data analysis
Visualize stock prices and trends
Compute moving averages and returns
Scale closing price data
Create time-series sequences (100 days lookback)
Train LSTM model
Predict stock prices
Evaluate model using RMSE
Save trained model

<img width="1238" height="441" alt="image" src="https://github.com/user-attachments/assets/e751ffdc-76a5-4172-97ab-b57f9c767fe8" />
<img width="1238" height="509" alt="image" src="https://github.com/user-attachments/assets/4d66ef22-af67-4a3c-ab2d-5d0c620cdef9" />
<img width="1238" height="509" alt="image" src="https://github.com/user-attachments/assets/0555c574-850c-4912-a7c3-ec2dcbf44f28" />
<img width="1254" height="441" alt="image" src="https://github.com/user-attachments/assets/12182fd9-f718-4e34-85a2-2e2481f3c580" />




