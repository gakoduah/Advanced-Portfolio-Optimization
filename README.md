# Advanced Portfolio Optimization System

![Tail Dependence Network](tail_dependence.png)  
*Visualization of tail risk dependencies between portfolio assets*

## 🔍 Overview
A production-grade portfolio optimization system blending:
- **Classical finance** (Markowitz optimization, EVT risk modeling)
- **Machine learning** (LSTM return forecasting, Random Forest covariance estimation)
- **Risk management** (copula simulations, regime detection)

**Key Features**:
- 3 portfolio strategies: Minimum Variance, Maximum Sharpe, ML-Enhanced
- Dynamic risk-adjusted position sizing
- Interactive Plotly dashboards for real-time monitoring

## 📊 Key Results
| Metric                  | Minimum Variance | Max Sharpe | ML-Enhanced |
|-------------------------|------------------|------------|-------------|
| CAGR (2018-2023)        | 12.1%           | 15.8%      | 15.2%       |
| Volatility              | 18.3%           | 22.7%      | 19.1%       |
| EVT VaR (95%)           | 6.2%            | 9.1%       | 7.96%       |
| Max Drawdown            | -24.3%          | -31.7%     | -26.5%      |

## 🛠️ Implementation Highlights

### Core Technologies
```python
- yfinance (data)
- Scipy (optimization) 
- TensorFlow/Keras (LSTMs)
- Scikit-learn (Random Forests)
- Copulae (dependency modeling)
- Plotly (visualization)
