# Insider Trading
This project is meant to explore possible trading strategies built on insider trading information from SEC Form 4s.

The project directory consists of the following
```
├── data                                 # Folder with all the data
  ├── insider_data                       # Insider trades by sticker, scraped from OpenInsider.com
  ├── stock_data                         # Historical OHLC data from Yahoo Finance
  ├── by_mcap                            # Merged data organized by mcap
├── strategy_tester.py                   # Main framework to test insider data with BackTrader
├── insider_methods.py
└── README.md
```
