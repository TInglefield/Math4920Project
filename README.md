# Statistical Arbitrage Trading Strategy (Pairs Trading)
## Overview
This project implements a statistical arbitrage trading strategy using pairs trading, designed to identify and exploit price discrepancies between cointegrated stock pairs. The strategy is implemented in Python and aims to capitalize on the mean-reverting nature of stock price spreads.

## Features
**Cointegration Tracking**: Identifies and tracks stock pairs that are cointegrated, ensuring the pairs move together over time.

**Spread Monitoring**: Calculates the spread between stock prices and monitors it daily. Trades are triggered when the spread deviates more than 2 standard deviations from its historical mean.

**Liquidity Check**: Ensures that the stocks in the pairs are highly liquid before initiating trades.

**Weekly Re-evaluation**: Assesses the cointegration status of stock pairs on a weekly basis. Trades are closed if pairs are no longer cointegrated or if liquidity conditions change.

## Data Sharing Restrictions
Please note that the stock price data used in this project was provided by Amila Muthunayake and is subject to specific usage restrictions. As per the terms agreed upon with the professor, we are unable to share this data publicly. However, the methodology and code for the trading strategy are fully available for review and use. If you are interested in replicating the results, you will need to acquire your own stock price data.
