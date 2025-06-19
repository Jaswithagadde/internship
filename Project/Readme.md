Project Report: Stock Price Trend Prediction Using LSTM 
1. Project Title 
Stock Price Trend Prediction with LSTM 
2. Objective 
To develop a deep learning model using Long Short-Term Memory (LSTM) networks that 
can accurately predict stock price trends based on historical data. 
3. Tools and Technologies 
• Python: Programming language used 
• yFinance API: To fetch historical stock market data 
• Pandas, NumPy: Data manipulation and preprocessing 
• Matplotlib: Data visualization 
• scikit-learn: Data normalization 
• Keras with TensorFlow backend: To build and train LSTM models 
• Google Colab: Training environment (cloud-based) 
• (Optional) Streamlit: For deploying the model as a web app 
4. Dataset 
• Source: Yahoo Finance (via yfinance) 
• Ticker Used: AAPL (Apple Inc.) 
• Date Range: 2015-01-01 to 2024-12-31 
• Features Used: Closing price 
5. Methodology 
Step 1: Data Collection 
• Fetched Apple stock data using yfinance. 
• Focused on the Close price for modeling. 
Step 2: Data Preprocessing 
• Scaled the data using MinMaxScaler (range [0, 1]). 
• Created sequences of 60-day windows to feed into the LSTM. 
Step 3: Model Building 
• Constructed an LSTM model with: 
o Two LSTM layers 
o Dropout layers to prevent overfitting 
o Dense output layer for regression 
• Compiled using adam optimizer and mean_squared_error loss. 
Step 4: Training 
• Split the data into 80% training and 20% testing sets. 
• Trained the model for 20 epochs with a batch size of 32. 
Step 5: Evaluation 
• Predicted stock prices on test data. 
• Inverse-transformed predictions to original price scale. 
• Plotted predicted vs actual values to visualize performance. 
6. Results 
• The predicted values closely follow the actual values. 
• Model is able to capture general trends and short-term fluctuations. 
• Performance could be improved further with more features (volume, indicators). 
7. Sample Output 
Graph: 
• X-axis: Time (days) 
• Y-axis: Stock price 
• Black Line: Actual prices 
• Green Line: Predicted prices 
The graph demonstrates a close match between predicted and 
actual values for test data. 
8. Optional Enhancements 
• Add technical indicators (RSI, SMA, EMA) as input features 
• Multi-day forecasting (e.g., next 7 days) 
• Deploy model with a real-time input dashboard using Streamlit 
• Hyperparameter tuning for better accuracy 
9. Conclusion 
This project successfully demonstrates how LSTM networks can be used to model time-series 
data like stock prices. Although not meant for financial advice, this model can serve as a 
basis for building more advanced forecasting systems by integrating multiple features and 
technical indicators. 
10. Deliverables 
• LSTM_Stock_Price_Prediction.ipynb: Colab-compatible Jupyter notebook 
• README.md: Documentation file 
• sample_plot.png: Visualization of predictions (optional) 
• lstm_model.h5: Trained model file (optional) 
• streamlit_app.py: Web interface (optional) 
