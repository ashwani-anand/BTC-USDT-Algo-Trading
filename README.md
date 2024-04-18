# BTC-USDT-Algo-Trading

## Overview
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

## Usage
1. Clone the repository to your local machine.
2. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```
3. Prepare historical market data in CSV format (e.g., `btc_1h.csv`).
4. Run the `main.py` script to execute the trend-following strategy with risk management:
   ```
   python main.py
   ```

## File Structure
- `main.py`: Main script to execute the strategy and display results.
- `strategy.py`: Contains the implementation of the trend-following strategy with risk management.
- `visualization.py`: Provides functions for visualizing trade signals and performance metrics.
- `btc_1h.csv`: Example historical market data for backtesting.

## Results
After running the `main.py` script, the program will output performance metrics and display visualizations of trade signals and strategy performance. These results can be used to assess the effectiveness of the trend-following strategy with risk management.

## Acknowledgements
- We acknowledge the valuable feedback and support from the programming and trading communities.
- We draw inspiration from various sources including academic research, industry experts, and successful trading strategies.

## Contributors
- Aman Kumar Verma: Team Lead/ Coordinator
- Ashwani Anand: ML developer
- Naira Anjum: Tester
- Pranamya R. Bairy: Researcher

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
