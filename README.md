# Trading Bot Using Sentiment Analysis
Harnessing Sentiment Analysis for Automated Trading on Alpaca Broker

This project introduces a trading bot developed to operate on the Alpaca brokerage platform. The bot makes strategic use of position sizing to optimize the quantity of each order and implements stop loss and take profit limits to define the conditions under which securities are bought or sold. 

Furthermore, the bot leverages natural language processing techniques to extract and analyze financial news, employing the FinBERT model to gauge market sentiment and to determines the most opportune moments to execute trades. To backtest the bot and evaluate its performance, historical market data from Yahoo Finance will be utilized to assess the effectiveness of the trading strategies implemented.

## Run the Bot:

1. Create a virtual environment '''conda create -n trader python=3.10'''
2. Activate it '''conda activate trader'''
3. Install all dependencies '''pip install -r requirements.txt'''
4. Update the '''API_KEY''' and '''API_SECRET''' with values from your Alpaca account
5. Run the bot '''python Trading_Bot.py'''
