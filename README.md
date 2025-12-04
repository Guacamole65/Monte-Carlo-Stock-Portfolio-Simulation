#Monte Carlo Stock Portfolio Simulator

This repository contains Python code for simulating the potential future performance of a stock portfolio using the Monte Carlo method. 
The simulation models asset price movements based on historical returns and volatility from which I computed the covariance matrix of constituents.
I ran hundreds of independent trials to project a range of possible portfolio return over a specified time horizon (252 days). 
This approach provides valuable insights into risk and return, helping users estimate the probability of reaching specific financial targets.

Features : 
  - Data Acquisition: Fetches historical stock price data for multiple assets using a reliable financial data library (e.g., yfinance).
  - Parameter Calculation: Calculates key statistical inputs for the simulation, including daily returns, mean return, and the covariance matrix for the selected assets.
  - Monte Carlo Simulation: Runs a specified number of independent trials to project the portfolio's value over a given time horizon.
  - Visualization: Generates informative plots of the simulation results, including the projected path fan-out and a histogram of final portfolio values.

This project is currently under active development. Future iterations will incorporate advanced quantitative finance techniques, expanding the simulation capabilities and analysis features.
