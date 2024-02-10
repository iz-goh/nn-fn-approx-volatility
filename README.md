# Neural Network Functional Approximation of Stock Market Volatility

## Description
In this project, I attempt to use a regular feed forward neural network as a function approximator to approximate the volatility of a stock market index. The predictors used in this project include economic data such as CPI, GDP, Unemployment Rate, Fed Funds Rate, as well as the volatility of the market over the past 5 days.

## Data sets used
* USA Consumer Price Index (CPI) -- FRED Economic Data
* Daily Effective Federal Reserve Funds Rate (DFF) -- FRED Economic Data
* USA Gross Domestic Product (GDP) -- FRED Economic Data
* USA Unemployment Rate (UNRATE) -- FRED Economic Data
* Volatility of the previous 5 days -- Calculated from SPY data

## Packages used
Pandas is for data cleaning, PyTorch is used for the creation and evaluation of the Neural Network, and Matplotlib to visualise.

## Usage
Feel free to download the project and experiment with the neural network, improve it, and create a pull request should you have any suggestions for improvement of the project.