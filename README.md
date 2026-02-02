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

<img width="580" height="394" alt="image" src="https://github.com/user-attachments/assets/cc9ea77f-96f9-4245-9e5a-5ca9d506ac6a" />
<img width="700" height="482" alt="image" src="https://github.com/user-attachments/assets/3d21242c-d530-41af-9e8f-06dd3d13dfb9" />
<img width="850" height="571" alt="image" src="https://github.com/user-attachments/assets/f70d5bb6-9d8a-497c-acff-2a952de8422d" />



