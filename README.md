# Quant Risk Engine
- A Quantitative Risk Management and Portfolio Optimization engine in Python.This project combines statistical modeling, risk metrics (VaR, CVaR), Monte Carlo simulation, Extreme Value Theory, and a custom neural network optimizer to build and backtest portfolio strategies. Used skills from DataCamp Applied Finance in Python. I would really appreciate any improvements that can be made to this model. 
# Features
- Historical, Parametric (Normal & t), Monte Carlo, and EVT-based Value at Risk (VaR) and Conditional VaR (CVaR)
- Efficient CVaR optimization using PyPortfolioOpt
- Custom Neural Network in TensorFlow with dynamic loss:
  - Minimum Volatility
  - Maximum Return
  - Maximum Sharpe Ratio
  - Minimize CVaR(Tail Risk)
- Backtesting and visualization for cumulative returns, VaR/CVaR, KDE fit and GEV plot for EVT- based tail risk
# Techonologies used
- Python
- Numpy, Pandas, Matplotlib, Seaborn
- Scipy
- PyPortfolioOpt
- TensorFlow & TensorFlow Probability
- yfinance
