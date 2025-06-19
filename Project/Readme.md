# 📈 Stock Price Trend Prediction with LSTM

Predict future stock prices using deep learning (LSTM) and visualize the trends with historical data and indicators.

## 🚀 Objective
To build an LSTM-based neural network that can predict stock price trends using past data. Optional: Integrate technical indicators like Moving Average and RSI.

## 🧰 Tools & Technologies

- **Python** (Pandas, NumPy)
- **TensorFlow / Keras** (LSTM Model)
- **yFinance** (Stock Data API)
- **Matplotlib** (Plotting)
- **Scikit-learn** (Preprocessing)
- **Google Colab** (Training)
- **Streamlit** (Optional Dashboard Deployment)

## 📂 Project Structure
📦 stock-price-lstm ├── LSTM_Stock_Price_Prediction.ipynb # Jupyter Notebook (Colab-ready) ├── lstm_model.h5 # Trained model (after saving) ├── streamlit_app.py # (Optional) Streamlit web app ├── README.md # Project documentation └── requirements.txt # Python dependencies




## 📊 Features

- Download stock data with `yFinance`
- Normalize and preprocess data for LSTM
- Build & train a multi-layer LSTM model
- Plot actual vs predicted closing prices
- Optionally integrate:
  - Simple Moving Average (SMA)
  - Relative Strength Index (RSI)
- Optional Streamlit app for real-time interaction



## 🔧 How to Run

### 🔹 Jupyter Notebook (Google Colab)
1. Clone or download the repo
2. Open `LSTM_Stock_Price_Prediction.ipynb` in [Google Colab](https://colab.research.google.com/)
3. Run cells in order
4. The model will:
   - Train on historical stock data
   - Predict test data
   - Plot predictions vs actual prices

✅ Deliverables
 Jupyter Notebook (.ipynb)
 Trained Model (.h5)
 Graphs & Visualizations
 (Optional) Live Streamlit Link

📌 Future Enhancements
Multi-feature training (Volume, MA, RSI)
Hyperparameter optimization
Multi-day future predictions
Sentiment analysis integration (news headlines)
📜 License
This project is licensed under the MIT License. Free to use and modify.

🤝 Acknowledgments
Yahoo Finance API
TensorFlow/Keras
Streamlit
