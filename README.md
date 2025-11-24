# Stock_Price_Forecasting
Stock market prediction is challenging due to high volatility and non-linearity. This project uses LSTM networks to forecast stock prices based on historical data

Objectives
- Download historical stock data
- Visualize using candlestick charts
- Preprocess and scale data
- Build and train an LSTM model
- Predict future prices

Technologies Used
Python, Pandas, NumPy, Matplotlib, Plotly, TensorFlow, Scikit-learn, Google Colab

Dataset Description
Data downloaded from Yahoo Finance (2015–2025), including OHLC and Volume.

System Architecture
1. Data collection
2. Visualization
3. Preprocessing
4. LSTM model
5. Training
6. Prediction
7. Methodology
Data cleaned, scaled, and structured into 60-day sequences for prediction.

LSTM Model
Two LSTM layers + Dense output layer. Uses Adam optimizer and MSE loss.

Model Training
Trained for 20 epochs, batch size 32.

Results & Visualization
- Candlestick chart
- Actual vs predicted plot
- Next-day price prediction

Advantages
Handles long-term dependencies and time-series patterns well.

Limitations
Cannot predict sudden market events; requires tuning.

Future Enhancements
Add indicators (RSI, MACD), multi-feature LSTM, dashboards, ARIMA, Prophet.

Conclusion
LSTM successfully forecasts trends and forms a strong base for financial ML projects.
