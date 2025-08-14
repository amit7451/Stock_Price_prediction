# Stock Price Prediction with LSTM Neural Network



## Overview
This project implements a Long Short-Term Memory (LSTM) neural network for stock price prediction using historical data. The solution runs entirely in Google Colab and provides:
- Historical price analysis
- Future price forecasting
- Visualization of predictions vs actual prices
- Model performance metrics

## Features
- **End-to-end pipeline**: From data collection to prediction visualization
- **LSTM architecture**: Optimized for time-series forecasting
- **Interactive visualizations**: Plotly-based charts
- **Automatic data retrieval**: Yahoo Finance API integration
- **30-day forecast**: Future price predictions
- **Model evaluation**: RMSE metrics for performance validation

## Requirements
- Google Colab account
- Internet connection
- Python 3.7+

## Installation & Setup
```bash
# No installation required! Simply:
1. Open Google Colab (colab.research.google.com)
2. Create new notebook
3. Paste provided code
4. Run all cells
```
## Usage
# Default runs for Apple (AAPL)
ticker = 'AAPL'
start_date = '2010-01-01'
end_date = '2023-12-31'

## Customisation

-  Change stock symbol
ticker = 'MSFT'  # Microsoft

-  Adjust date range
start_date = '2015-01-01'
end_date = '2024-05-31'

-  Modify forecast period
future_days = 45  # 45-day forecast


## Project Structure
stock-prediction/
├── stock_prediction.ipynb        # Main Colab notebook
├── README.md                     # This documentation




