# Stock Closing Price Prediction

## Project Overview
This project employs machine learning to forecast stock closing price trends. By analyzing historical market data and integrating advanced technical indicators, it offers a robust framework for informed decision-making. The XGBoost model achieves approximately 80% accuracy in predicting 7-day trends. This repository demonstrates the integration of technical indicators such as EMA, RSI, MACD, and Bollinger Bands to enhance model performance and predictions.

---

## Goals
- Predict stock price trends for short-term (7-day) and long-term (30-day) analysis.
- Incorporate advanced technical indicators for feature engineering.
- Visualize predictions using interactive plots.

---

## Technologies and Tools Used
- **Programming Language:** Python
- **Libraries:**
  - Data Processing: Pandas, NumPy
  - Visualization: Matplotlib
  - Machine Learning: XGBoost, Scikit-learn
- **Data Source:** Yahoo Finance (via yfinance library)

---

## Setup and Usage Instructions

### Prerequisites
- Python 3.8 or higher.
- Install the required libraries using `pip`.

### Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/[your-username]/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `StockClosingPricePrediction.ipynb` and execute the cells to fetch data, train the model, and visualize predictions.

4. **Modify Parameters:**
   - Within the notebook, update the `stock_symbol` variable to the desired stock ticker (e.g., "AAPL" for Apple).
   - Adjust the date range in the `fetch_stock_data` function as needed.

---

## Features and Technical Indicators
- **Exponential Moving Averages (EMA):** Tracks momentum by smoothing price data.
- **Bollinger Bands:** Identifies volatility and potential price reversals.
- **MACD (Moving Average Convergence Divergence):** Measures trend strength and direction.
- **RSI (Relative Strength Index):** Identifies overbought/oversold conditions.
- **Lagging Features:** Historical close prices for trend prediction.

---

## Sample Results
Below is a sample graph demonstrating the model's predictions:

![Model Output](images/Predictions.png "Printed Model Output")
![Sample Graph](images/SampleStockImage.png "Sample Graph of Predicted Trends")


## Future Improvements
- **Real-Time Data Integration:** Enable live stock data fetching via APIs.
- **Enhanced Visualizations:** Add dashboards for comprehensive analysis.
- **Multi-Asset Analysis:** Expand to include multi-stock predictions.
- **Sentiment Analysis:** Integrate news and social media sentiment for better predictions.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contributing
Contributions are welcome! Feel free to fork the repository, create pull requests, or submit issues for feature requests and bug fixes.

---

## Acknowledgments
- Thanks to Yahoo Finance for the stock data API support.
