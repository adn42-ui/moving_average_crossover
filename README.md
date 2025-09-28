
INTRODUCTION
This project implements a simple Moving Average Crossover trading strategy using Python.
The strategy tracks two moving averages of a stock price:

Short-term moving average (default: 20 days)

Long-term moving average (default: 50 days)

Buy Signal → when the short-term MA crosses above the long-term MA.
Sell Signal → when the short-term MA crosses below the long-term MA.

This is a popular technical analysis technique for identifying potential trend changes in financial markets.

Tools & Libraries
yfinance → Download daily stock data from Yahoo Finance
pandas → Data handling and calculations
matplotlib → Data visualization

Project structure
moving_average_crossover/
│── notebook/
│   └── moving_average_crossover.ipynb   # Main Jupyter Notebook
│── README.md                            # Project documentation

How to Run

1.Clone this repository:
git clone https://github.com/adn42-ui/moving_average_crossover.git
cd moving_average_crossover

2.Install dependencies:
pip install yfinance pandas matplotlib

3.Open the Jupyter Notebook:
jupyter notebook notebook/moving_average_crossover.ipynb

4.Run all cells to see signals and charts

Example Output
When you run the notebook, you'll see a chart showing:
stock closing price (gray line)
20-day moving average(blue)
50-day moving average (red)
Buy signals (green arrows)
sell signals (red arrows)

Disclaimer
This project is for educational purposes only. 
It does not constitute financial advice. Backtest and validate before applying to real trades.
