# Empirical Asset Pricing with Recurrent Neural Networks (RNN)

## Overview
This repository contains an empirical asset pricing strategy that leverages a Recurrent Neural Networks (RNN) model. The strategy has been back-tested on a dataset of 2,000 stocks over a 21-year investment horizon. The goal is to explore the predictive power of RNNs in the context of financial markets and compare their performance against traditional tree-based models.

## Key Features
- RNN Model: The heart of this strategy is an RNN model trained on historical stock price data. The RNN captures temporal dependencies and patterns in stock returns, allowing it to make predictions beyond simple statistical models.
- Back-Testing: We rigorously back-tested the RNN-based strategy using historical data. This involved simulating trades, calculating portfolio returns, and assessing risk-adjusted performance metrics.
- Comparison with Tree-Based Models: We compare the RNN's performance against popular tree-based models (such as random forests, and gradient boosting, adaBoost) in terms of monthly average returns and the Sharpe ratio.

## Repository Structure
- `data/`: Contains the historical stock price data used for training and testing.
- `models/`: Stores the trained RNN model and other benchmark models.
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and back-testing.
- `results/`: Holds the back-tested results, performance metrics, and visualizations.
- `README.md`: You're reading it! This file provides an overview of the project.

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python packages (e.g., TensorFlow, pandas, scikit-learn).
3. Explore the Jupyter notebooks in the `notebooks/` directory to understand the data preprocessing, model training, and back-testing process.
4. Run the back-tests and analyze the results.

## Usage
1. Load historical stock price data (e.g., from Yahoo Finance or Quandl, Alpaca, csv file).
2. Preprocess the data (handle missing values, calculate returns, etc.).
3. Train the RNN model using the preprocessed data.
4. Back-test the strategy using the trained model.
5. Compare the RNN's performance with other models.

## Conclusion
Empirical asset pricing using RNNs offers exciting possibilities for enhancing investment strategies. By leveraging deep learning techniques, we can potentially uncover hidden patterns and improve risk-adjusted returns. However, thorough testing and validation are crucial before deploying such models in real-world scenarios.

Feel free to explore the code, experiment with different architectures, and contribute to this research!

---

*Disclaimer: This repository is for educational and research purposes only. It does not constitute financial advice, and any investment decisions should be made based on thorough analysis and consultation with financial professionals.*

