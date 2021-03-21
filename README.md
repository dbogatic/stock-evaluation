#
# Stock Evaluation Tools

![stocks.jpg](images/stocks.jpg)
#
This repo contains a set of tools that an investor can use to gain better understanding about the stock he/she is interested in. It does not serve as a recommendation to buy or sell a stock, but to aid in forming an educated guess about the potential future stock price movement and consequently in making a buy/sell/hold decision regarding a stock that is being analyzed.

The tools included here are not the only tools available to be used. The reason I included them was that I believe no single tool or a model can be sufficient to understand all the forces that contribute to a stock price movement. 

The set of tools included in this repo could be classified into:

* Technical analysis tools (SMA signals, EWMA signals, Bollinger Bands).
* Fundamental analysis (using financial data via YahoofFinancials API).
* Deep machine learning model (LSTM).
* Probability based prediction model (Monte Carlo simulation)
* Natural language processing (NLP sentiment analysis).

I believe that by using the above analysis tools together one has much better chances at making correct predictions regarding future stock prices.
#
## How to Use the Repository

There is not a pre-defined way how to use the tools included in the repo. However, every analysis starts with data collection. In order to collect historical stock prices you should start with:

* [yahoo_historical notebook](yahoo_historical.ipynb)

The stock price data pulled using Yahoo_Financials API are stored in Resources folder in [stock historical prices](Resources/stock_historical_prices.csv) table and are the basis for analysis using the rest of the tools in this repo. You can find API documentation at [YahooFinancials](https://pypi.org/project/yahoofinancials/) website.

I would strongly suggest to read pseudo-code that is part of the code, to better understand how these models work, results obtained as well as additional tweaks that could be done (e.g. LSTM model hyperparameter tuning), to improve the prediction performance of the model.

You will need to change the input within the code in several places and I did my best to instruct this where needed. 

#
## Notes: 

The tools in this repo are product of my studying while enrolled in FinTech Bootcamp program, provided by Trilogy Education Services, at Rice University in Houston, TX. 

This repo is work in progress, so it is subject to further changes/improvements. 

If you come across errors while using the tools, please let me know so I can correct them. 

If you have any suggestions and ideas how this repo or the code could be improved, I welcome such suggestions. 

#
© 2020 Author: Dragan Bogatic
#