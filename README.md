# Portfolio Optimizer

**Portfolio Optimizer** is a Python-based tool designed for constructing, analyzing, and optimizing investment portfolios. It utilizes financial data from Yahoo Finance and advanced portfolio optimization techniques from the PyPortfolioOpt library. This tool helps users benchmark custom portfolios, optimize allocations, and compare their performance against market indices (e.g., Nifty 50).

---

## Key Features

### 1. Custom Portfolio Analysis
Analyze the performance of a custom portfolio by calculating:
- **Cumulative Return**
- **Annual Return**
- **Volatility**
- **Sharpe Ratio**
- **Maximum Drawdown**

### 2. Portfolio Optimization
Optimize portfolio weights to maximize the Sharpe Ratio while adhering to constraints:
- Minimum and maximum stock allocations.
- Option to retain underperforming stocks.
- Compare optimized portfolio metrics with the original portfolio.

### 3. Market Benchmarking
Compare portfolio performance against a benchmark index (e.g., Nifty 50) by calculating:
- **Annual Return**
- **Volatility**
- **Sharpe Ratio**
- **Maximum Drawdown**

### 4. Visualization
Generate cumulative return comparison plots for:
- Custom Portfolio (Benchmark)
- Optimized Portfolio
- Market Index (e.g., Nifty 50)

### 5. Stock Insights
Retrieve stock-specific details such as:
- **Company Name**
- **Sector**
- **Industry**

### 6. Data-Driven Insights
- Identify underperforming stocks using historical data.
- Compare weight changes and return differences between the original and optimized portfolios.

---

## Technical Details

- **Data Sources:** Yahoo Finance (via `yfinance` library)
- **Optimization Engine:** PyPortfolioOpt
- **Programming Language:** Python
- **Visualization Library:** Matplotlib

### Dependencies
- `yfinance`
- `pandas`
- `numpy`
- `PyPortfolioOpt`
- `matplotlib`

---

## Workflow

1. **Define a Custom Portfolio:** Provide stock tickers with initial weights.
2. **Analyze the Portfolio:** Calculate performance metrics and sectoral breakdown.
3. **Optimize the Portfolio:** Adjust weights for maximum Sharpe Ratio.
4. **Compare with Benchmark:** Evaluate portfolio performance against a market index.
5. **Visualize Results:** Plot cumulative returns to observe trends and performance.

---

## Output

1. **Portfolio Summaries:** Get a detailed breakdown of stock allocations, returns, and risks.
2. **Performance Metrics:** Access insights into cumulative returns, annualized performance, and risk-adjusted measures.
3. **Comparison Plot:** Visualize portfolio performance trends against benchmarks.

---

## Applications
* Perform financial analysis and support investment decision-making.
* Evaluate the impact of portfolio diversification and optimization.
* Understand the contribution of individual stocks to overall portfolio performance.

