# Crypto-Trading-Bot
Cryptocurrency trading bot, developed following this guide:

https://www.learndatasci.com/tutorials/algo-trading-crypto-bot-python-strategy-backtesting/

### Directory
cd into `Crypto-Trading-Bot\ft_userdata\user_data`

### Run HyperOpt (generate parameters):
`docker-compose run --rm freqtrade hyperopt --config user_data/learndatasci-config.json --strategy RsiStrat --epochs 50 --spaces default --hyperopt-loss SharpeHyperOptLoss`

### Run Backtest:
`docker-compose run --rm freqtrade backtesting --config user_data/learndatasci-config.json --strategy SampleStrategy`

### TODO LIST:
1. Set up Binance account(s): https://www.freqtrade.io/en/stable/configuration/#switch-to-production-mode
2. Set up Binance API with trading bot
3. Invest $20?
4. Profit!
5. Generate better strategy, invest in normal stocks?
