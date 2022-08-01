# Crypto-Trading-Bot
Cryptocurrency trading bot, developed following this guide:

https://www.learndatasci.com/tutorials/algo-trading-crypto-bot-python-strategy-backtesting/



Commands:

### Run HyperOpt (generate parameters)
docker-compose run --rm freqtrade hyperopt --config user_data/learndatasci-config.json --strategy RsiStrat --epochs 50 --spaces default --hyperopt-loss SharpeHyperOptLoss`

### Run Strategy:
docker-compose run --rm freqtrade backtesting --config user_data/learndatasci-config.json --strategy SampleStrategy
