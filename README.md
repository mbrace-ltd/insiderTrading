# Insider Trading
## Background


## Project Description
This project is meant to explore possible trading strategies built on insider trading information from SEC Form 4s.
Insider trading data for 3700 NASDAQ-listed companies was scraped from <a href="">OpenInsider.com</a>.
Historical stock prices for the same companies was scraped from YahooFinance via yfinance. 
The generated strategies were backtested via Backtrader.

Documentation for the project is available at <a href="https://www.mbrace.ltd/projects/insider_trading"> Mbrace - Insider Trading</a>



The project directory consists of the following:
```
├── data                                 # Folder with all the data
  ├── insider_data                       # Insider trades by sticker, scraped from OpenInsider.com
  ├── stock_data                         # Historical OHLC data from Yahoo Finance
  ├── by_mcap                            # Merged data organized by mcap
├── strategy_tester.py                   # Main framework to test insider data with BackTrader
├── insider_methods.py
└── README.md
```

**insider_methods.py** contains the main methods used for acquring data and backtesting strategies.
**strategy_tester.py** contains methods cleaning the data and building a Backtrader strategy to analyse returns.


## Results

### Returns (%) by Market Capitalization:
![image](https://user-images.githubusercontent.com/96435975/152239564-34f4daec-eb6c-4881-b781-9ab85a2b3621.png)

### Returns (%) by Industry:

![image](https://user-images.githubusercontent.com/96435975/152239764-6a074f7a-a6f6-4883-b6bc-1b4edc54c419.png)

### Individual Best/Worst performing tickers:
![image](https://user-images.githubusercontent.com/96435975/152239884-0f65dadf-551a-481f-9ef7-741b2d1f53ca.png)


