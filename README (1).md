# 📈 Time Series Stock Forecasting Project

This project performs time series analysis and forecasting of stock market data using traditional statistical models and deep learning.

## ✅ Project Objectives
- Perform time series analysis on stock data.
- Compare ARIMA, SARIMA, Prophet, and LSTM models.
- Visualize forecast accuracy and trends.
- Use deep learning (LSTM) for future price prediction.

## 🛠️ Technologies Used
- **Python**, **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Statsmodels**, **Scikit-learn**
- **Facebook Prophet**
- **TensorFlow/Keras** (for LSTM in Jupyter)
- *(Optional)* Streamlit for deployment

## 📁 Folder Structure
stock_forecasting_project/
├── data/
│ └── stock_data.csv
├── models/
│ └── lstm_model.ipynb
├── visualization/
│ └── interactive_plot.html
├── main_forecasting_notebook.ipynb
├── LSTM.html
├── requirements.txt
└── README.md

## 📊 Models Implemented
| Model   | Type         | Purpose                  |
|---------|--------------|--------------------------|
| ARIMA   | Statistical  | Basic time series model  |
| SARIMA  | Seasonal ARIMA | Captures seasonality  |
| Prophet | Additive model | Trend + seasonality |
| LSTM    | Deep Learning | Captures long-term patterns |

## 🔗 LSTM Jupyter Version
LSTM was executed successfully in Jupyter (`lstm_model.ipynb`) and exported as HTML (`LSTM.html`).

## 📌 Note
Modeling logic was included in one main notebook for unified execution. Separate scripts were used during development.
