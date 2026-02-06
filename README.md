# PPO Portfolio Optimization

A Deep Reinforcement Learning project implementing Proximal Policy Optimization (PPO) for dynamic multi-asset portfolio management.

## Project Overview
This project uses an Actor-Critic architecture to optimize a portfolio of 5 stocks (AAPL, MSFT, JPM, GOOGL, AMZN). The agent learns to rebalance weights to maximize risk-adjusted returns while considering transaction costs.

## Implementation Details
- **Algorithm:** PPO with Clipped Surrogate Objective.
- **Environment:** Custom Gymnasium-compatible MDP.
- **Features:** RSI, MACD, Rolling Volatility, and Log Returns.
- **Framework:** PyTorch & Gymnasium.

## Results
- **PPO Agent Return:** ~36.9% 
- **Benchmark (Buy & Hold):** ~37.9%
- **Analysis:** The agent successfully converged to the market trend, accounting for transaction costs and volatility penalties.
