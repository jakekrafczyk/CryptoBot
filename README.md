# CryptoBot(Kraken Exchange)

This project is largely being worked on outside of github, considering its probably not the best idea to be advertising my trading edges. That said, I'll be uploading any files here that aren't related to strategy. I'm currently working with kernc's backtesting.py repository([Backtesting](https://kernc.github.io/backtesting.py/)) as its object oriented and therefore better able to handle large datasets. May move on to askmike's Gekko bot([Crypto Bot](https://gekko.wizb.it/)) once I've drawn out enough insight through backtesting since it has live trading functionality.

kraken_req.py – Pulls live OHLCV data from Kraken's Public API. Set up for just daily and hourly XBT/USD but could easily be modified.

kchart.py – Imports the data from kraken_req and creates a candlestick chart overlayed with a horizontal bar chart displaying the Volume by Price. An option to add buy and sell signals is also available. The intent of these files is to eventually be a part of a fully automated trading bot, but I may end up using askmike's bot if it can provide the functionality I'm looking for. 
