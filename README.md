# Trading Bot Using Sentiment Analysis
Harnessing Sentiment Analysis for Automated Trading on Alpaca Broker

This project introduces a trading bot developed to operate on the Alpaca brokerage platform. The bot makes strategic use of position sizing to optimize the quantity of each order and implements stop loss and take profit limits to define the conditions under which securities are bought or sold. 

Furthermore, the bot leverages natural language processing techniques to extract and analyze financial news, employing the FinBERT model to gauge market sentiment and to determines the most opportune moments to execute trades. To backtest the bot and evaluate its performance, historical market data from Yahoo Finance will be utilized to assess the effectiveness of the trading strategies implemented.

## Run the Bot:

1. Create a virtual environment ```conda create -n trader python=3.10```
2. Activate it ```conda activate trader```
3. Install all dependencies ```pip install -r requirements.txt```
4. Update the ```API_KEY``` and ```API_SECRET``` with values from your Alpaca account
5. Run the bot ```python Trading_Bot.py```

## Setup Paper Trading Account:

Anyone globally can create an Alpaca Paper Only Account! All you need to do is sign up with your email address. If you do not already have an Alpaca trading account (whether paper or not), here are the steps to get started with one:

1. **Sign Up for an Alpaca Account**: Visit the Alpaca website and sign up for a paper trading account (https://alpaca.markets). During the sign-up process, you will be given the option to choose between a live trading account or a paper trading account. Select the paper trading option, which will allow you to trade with simulated money and test your strategies without financial risk.

2. **Complete the Registration**: Fill in all the required details in the registration form, including your email address, password, and any necessary personal information. After submitting the form, you'll need to verify your email address by clicking on the verification link sent to your email.

3. **Access the Paper Trading Dashboard**: Once your account is set up and you're logged in, navigate to the paper trading dashboard.

4. **Obtain Your API Key and Secret**: Look for a section in the dashboard related to API keys, often found in the account settings or configuration menu. Generate a new API key and secret from this section. Be sure to save both the API key and the secret in a secure place, as the API secret will not be shown again.

Your initial paper trading account is created with $100k balance as a default setting. You can reset the paper trading account at any time later with arbitrary amount as you configure.

## Documentation:

Alpaca Paper Trading Account: https://docs.alpaca.markets/docs/paper-trading
