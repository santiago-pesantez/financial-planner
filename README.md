# Financial planner
This repo implements two financial analysis tools in a single Jupyter notebook:

1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.
---
## Required libraries and dependencies
* os
* requests
* json
* pandas pd
* dotenv
* alpaca_trade_api
* MCForecastTools
* matplotlib