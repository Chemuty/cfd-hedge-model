CfD Hedge Model for Energy Trading

A (CfD) hedge model built for energy trading analysis. 
Models weather risk, runs Monte Carlo simulations, and provides an interactive dashboard.

## Features

- **Core CfD Model**: Calculate settlements for long/short positions with negative price support
- **Weather Risk Integration**: Temperature and wind speed drive demand and price scenarios  
- **Monte Carlo Simulation**: 10,000 weather scenarios with Value at Risk (VaR) calculation
- **Hedge Optimization**: Find optimal hedge ratio to minimize downside risk
- **Interactive Dashboard**: Streamlit web app for real-time scenario analysis

## Tech Stack

- Python 3.10+
- Pandas, NumPy
- Matplotlib, Plotly
- Streamlit

## Key Results

- Average monthly profit: £27,540
- 95% Value at Risk (VaR): £16,246
- Optimal hedge ratio: 100% of load exposure
