# market_strategy

MarketScanner

Overview:

MarketScanner is a Python class designed for performing technical analysis on asset data from various financial markets, with a focus on cryptocurrencies. It leverages predefined trading strategies to identify potential trading opportunities based on a combination of technical indicators.

Key Features:

Dynamic Query Generation:
Generates queries dynamically based on user-specified market type (e.g., 'crypto') to retrieve asset data.

Strategy Execution:
Executes multiple predefined trading strategies (str_1_up_trend, str_2_up_trend, etc.) using technical indicators such as RSI, EMA, MACD, CCI, ADX, and more.

Result Aggregation:
Aggregates results from different strategies, calculates the total number of strategies each asset meets, and ranks them based on effectiveness.

Backtesting:
Facilitates backtesting of trading strategies against historical market data obtained from a specified exchange.

Data Management:
Appends new results to an existing CSV file or creates a new file if none exists, ensuring seamless data integration and persistence.
