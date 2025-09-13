### INF601 - Advanced Programming in Python
### Jamie Smith
### Mini Project 1
 
 
# Project Title
 
MiniProject 1 - Stock Tickers
 
## Description
 
This program allows users to generate charts of the closing prices of their chosen stocks over the last 10 trading days. When the program runs, it looks up each stock ticker listed in the stocks file, retrieves the closing price data, and creates a graph for each stock. The graphs are saved in a folder named charts, which the program will automatically create if it does not already exist. The current stock tickers included in the program are:
- Tesla - TSLA
- Google - GOOG
- Microsoft - MSFT
- Palantir Technologies, Inc. - PLTR
- Nvidia - NVDA

## Getting Started
 
### Dependencies
 Please install the pip requirements:
```
pip install -r requirements.txt
```
 
### Executing program
 
To view different stocks, update the list of tickers stored in the mystocks variable inside the stocks file before running the program. Then run:
```
python main.py
```
 
## Authors
 
Jamie Smith
 
## Version History
 
* 0.1
    * Initial Release
 
## Acknowledgments
 
Inspiration, code snippets, etc.
* [Matplotlib Documentation](https://matplotlib.org/stable/users/index.html)
* [yfinance](https://ranaroussi.github.io/yfinance/)