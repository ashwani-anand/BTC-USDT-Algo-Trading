# BTC-USDT Algo Trading

This project implements a trend-following trading strategy with risk management techniques using Python and Backtrader. The strategy aims to capture trends in the BTC/USDT market while managing risk through position sizing and stop-loss mechanisms.

## Features

- Trend-following strategy based on moving averages.
- Risk management techniques including position sizing and stop-loss orders.
- Performance evaluation metrics such as profit, drawdown, win rate, Sharpe ratio, and Sortino ratio.
- Backtesting functionality to evaluate strategy performance using historical data.
- Visualization of trade signals and strategy performance.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- NumPy
- Backtrader

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ashwani-anand/BTC-USDT-Algo-Trading.git
    cd BTC-USDT-Algo-Trading
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare historical market data in CSV format (e.g., `btc_1h.csv`).
2. Run the `main.py` script to execute the trend-following strategy with risk management:
    ```bash
    python main.py
    ```

## File Structure

- `main.py`: Main script to execute the strategy and display results.
- `strategy.py`: Contains the implementation of the trend-following strategy with risk management.
- `visualization.py`: Provides functions for visualizing trade signals and performance metrics.
- `btc_1h.csv`: Example historical market data for backtesting.

## Results

After running the `main.py` script, the program will output performance metrics and display visualizations of trade signals and strategy performance. These results can be used to assess the effectiveness of the trend-following strategy with risk management.

## Contributors

- Aman Kumar Verma: Team Lead/Coordinator
- Ashwani Anand: ML Developer
- Naira Anjum: Tester
- Pranamya R. Bairy: Researcher

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## About

Build and backtest a trend-following trading strategy with Python and Backtrader. Analyze cryptocurrency market data, visualize strategy performance, and evaluate key metrics.
