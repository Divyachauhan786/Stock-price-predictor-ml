 📈 Apple Stock Price Predictor
This project predicts Apple Inc. (AAPL) stock prices using **Linear Regression** based on historical closing price data. It includes visualizations and model performance metrics.


 📂 Dataset

- **File Used:** `HistoricalQuotes.csv`
- **Source:** [Kaggle - Apple Historical Stock Data](https://www.kaggle.com/datasets/tarunpaparaju/apple-aapl-historical-stock-data)
- **Fields Used:** Date, Close

🔧 Features

- 📊 Predict the next day’s closing price of Apple stock
- 📈 Visualize historical trends and predictions
- 📉 Evaluate performance using:
  - Mean Squared Error (MSE)
  - R² Score
- 🧠 Model used: **Linear Regression** (from `scikit-learn`)

🧰 Libraries Used

- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `matplotlib` – for plotting
- `scikit-learn` – for machine learning

📊 Graphs Included

1. **Apple Stock Closing Price Over Time**
2. **Actual vs Predicted Prices (sample 100 points)**
3. **Last 90 Days Price Trend**

🧪 How to Run

1. Clone this repo or download the `.ipynb` file.
2. Download the dataset `HistoricalQuotes.csv` from [Kaggle](https://www.kaggle.com/datasets/tarunpaparaju/apple-aapl-historical-stock-data).
3. Open the notebook in **Google Colab** or **Jupyter Notebook**.
4. Upload the CSV file and run all cells.



 📌 Sample Output

Predicted next day's closing price: $181.24


💡 Future Enhancements

- Use LSTM or GRU for time series modeling
- Add technical indicators like RSI, SMA, EMA
- Deploy using Streamlit or Flask


🔒 Disclaimer

This project is for educational and experimental purposes only. It should **not** be used for real-time trading or financial advice.



🤝 Credits

- Dataset Source: [Kaggle - Apple Historical Stock Data](https://www.kaggle.com/datasets/tarunpaparaju/apple-aapl-historical-stock-data)
- Developed by: Divya Chauhan


