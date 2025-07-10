Postman Stock API Testing Project

A Postman project for testing stock market data using Alpha Vantage APIs (https://www.alphavantage.co/).

This Project includes:

- Symbol Search (Tesla)
- Daily Time Series (Tesla)
- Response structure validation
- Content validation (e.g., verify symbol name)
- Environment variables used: `base_url`, `api_key`

Collection #2 : Chained API testing.postman_collection
Objective: Request Chaining

Steps:
1. Search Company: Use `SYMBOL_SEARCH` to find a company symbol (e.g., `Tesla`)
2. Save Symbol: Extract symbol from response and store it in an environment variable
3. Get Stock Data: Use saved symbol in `TIME_SERIES_DAILY` to fetch stock price data
4. Validate Responses: Add assertions to ensure correct and complete data
