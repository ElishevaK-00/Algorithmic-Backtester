# Algorithmic Strategy Engine & Backtesting Environment

## Project Overview
This repository houses an object-oriented backtesting environment designed to evaluate rule-based systematic trading frameworks. The engine processes multiple years of historical market data to backtest execution strategies, compiling performance and risk-adjusted return metrics relative to a passive benchmark index.

## Methodology
- **Signal Generation:** Implements a classic Simple Moving Average (SMA) crossover execution strategy (50-day vs. 200-day window) to establish clear systematic "Buy" and "Sell" triggers.
- **Performance Compounding:** Dynamically calculates daily equity curves, tracking continuous portfolio returns based on strategy signals.
- **Benchmark Evaluation:** Automatically generates performance comparison vectors, calculating alpha generation, max drawdown, and overall strategy trade metrics.

## Core Technical Skills Displayed
- Object-Oriented Programming & Backtester Architecture
- Quantitative Strategy Development & Alpha Generation
- Mathematical Strategy Performance Analysis
