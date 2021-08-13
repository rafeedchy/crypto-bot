# crypto-bot
This project is with a goal to create an automated trading bot. We took etherium/usdt currency pairs and got the live price action data from binance API stream. 
I calculated the ATR function, Average True Range to identify a supertrend. if the price action enters into supertrend we will get a confirmation via email. 
I also added buy sell conditions. If the price enters into a supertrend and price is over 200EMA than we'll enter to the market. if price falls from supertrend we'll close
the market.
