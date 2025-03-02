# Bioinformatics Portfolio Analysis

This project performs portfolio analysis on bioinformatics companies using financial data. The analysis includes data collection, portfolio construction, performance evaluation, and visualization.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data Collection](#data-collection)
- [Portfolio Construction](#portfolio-construction)
- [Performance Evaluation](#performance-evaluation)
- [Visualization](#visualization)
- [Results](#results)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/yourrepository.git
    cd yourrepository
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook Bio\ portifolio.ipynb
    ```

2. Run the cells in the notebook to perform portfolio analysis on bioinformatics companies.

## Project Structure

- `Bio portifolio.ipynb`: The main Jupyter notebook containing the code for data collection, portfolio construction, performance evaluation, and visualization.
- `requirements.txt`: The list of required packages.
- `README.md`: This README file.

## Data Collection

Financial data is collected using the `financedatabase` and `yfinance` libraries. The `equities.search` function fetches bioinformatics companies based on specified criteria.

## Portfolio Construction

The portfolio is constructed by selecting bioinformatics companies and assigning weights to each stock. The initial and ending values of the portfolio are calculated based on the stock prices.

## Performance Evaluation

The performance of the portfolio is evaluated using metrics such as cumulative returns, daily returns, and volatility. The Sharpe ratio is also calculated to assess the risk-adjusted return of the portfolio.

## Visualization

The notebook provides various visualizations, including:
- Adjusted closing prices of the stocks
- Daily return distribution
- Correlation heatmap
- Cumulative returns over time
- Portfolio performance compared to benchmarks (XBI and SPY)

## Results

The notebook provides detailed analysis and visualizations of the bioinformatics portfolio's performance. It also compares the portfolio's performance with benchmarks.

## Example Output

```plaintext
Stocks in Portfolio
['AAPL', 'GOOGL', 'MSFT', 'AMZN', 'FB', 'TSLA', 'NVDA', 'NFLX', 'ADBE', 'PYPL', 'INTC', 'CSCO', 'ORCL', 'IBM', 'CRM', 'AMD', 'QCOM', 'TXN', 'AVGO']
______________________________________________________________________________________
Random Weights
[0.03745401 0.09507143 0.07319939 0.05986585 0.01560186 0.01559945 0.00580836 0.08661761 0.0601115  0.07080726 0.00205845 0.09699099 0.08324426 0.02123391 0.0181825  0.01834045 0.03042422 0.05247564 0.0431945 ]
______________________________________________________________________________________
Rebalanced Weights
[0.03745401 0.09507143 0.07319939 0.05986585 0.01560186 0.01559945 0.00580836 0.08661761 0.0601115  0.07080726 0.00205845 0.09699099 0.08324426 0.02123391 0.0181825  0.01834045 0.03042422 0.05247564 0.0431945 ]
______________________________________________________________________________________
Portfolio Return
12.3456%
______________________________________________________________________________________
Expected Portfolio Volatility
15.6789%
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
