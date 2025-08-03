# 📈 Google Stock Price Prediction using LSTM (RNN)

This project builds a Recurrent Neural Network (RNN) using Long Short-Term Memory (LSTM) layers to predict the **opening stock price** of Google based on historical data. The model is trained using past 60 days of prices to predict the next day's price.

---

## 🚀 Project Overview

- **Goal**: Predict future Google stock prices using historical data
- **Model**: 4-layer stacked LSTM with Dropout for regularization
- **Input**: Past 60 days of "Open" stock prices
- **Output**: Predicted "Open" stock price for the next day

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## 📁 Project Structure

```bash
google-stock-price-prediction/
├── Google_Stock_Price_Train.csv     # Training data (2012–2016)
├── Google_Stock_Price_Test.csv      # Testing data (2017)
├── rnn.py                           # Main script (builds and runs the LSTM)
└── README.md                        # Project documentation
