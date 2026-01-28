# Time Series Forecasting for Portfolio Management Optimization

## 📊 Project Overview
Complete implementation of time series forecasting and portfolio optimization for GMF Investments.

## 🎯 Objectives Completed
1. **Task 1**: Data preprocessing and exploratory analysis
2. **Task 2**: Time series modeling (ARIMA vs LSTM)
3. **Task 3**: Future market trends forecasting  
4. **Task 4**: Portfolio optimization using Modern Portfolio Theory
5. **Task 5**: Strategy backtesting and validation

## 📈 Key Findings
- **Best Model**: LSTM outperformed ARIMA on all metrics
- **TSLA Forecast**: Bearish outlook (-53.6% over 12 months)
- **Recommended Portfolio**: Minimum Volatility Portfolio
- **Allocation**: TSLA 20%, BND 50%, SPY 30%

## 🚀 Getting Started
```bash
# Clone repository
git clone https://github.com/yourusername/time-series-portfolio-optimization.git

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install requirements
pip install -r requirements.txt

# Run notebooks in order:
# 1. 01_data_exploration.ipynb
# 2. 02_time_series_modeling.ipynb
# 3. 03_future_forecasting.ipynb
# 4. 04_portfolio_optimization.ipynb
# 5. 05_strategy_backtesting.ipynb