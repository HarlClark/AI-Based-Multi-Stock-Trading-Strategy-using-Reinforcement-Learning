# 📊 AI-Based Multi-Stock Trading Strategy using Reinforcement Learning

## 🚀 Overview
This project develops an intelligent stock trading agent using Reinforcement Learning (PPO algorithm). The model is trained on historical stock data of multiple companies and uses technical indicators to make trading decisions such as Buy, Sell, or Hold.

---

## 🧠 Features
- Multi-stock data handling (10 major companies)
- Technical indicators:
  - SMA (Simple Moving Average)
  - EMA (Exponential Moving Average)
  - RSI (Relative Strength Index)
  - MACD & Signal Line
  - Bollinger Bands
- Reinforcement Learning using PPO (Proximal Policy Optimization)
- Custom OpenAI Gym trading environment
- Performance metrics:
  - Win Rate
  - Sharpe Ratio
  - Maximum Drawdown
- Visualization of portfolio performance

---

## 🏗️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Gymnasium (OpenAI Gym)
- Stable-Baselines3 (PPO)
- yFinance API

---

## 📂 Project Workflow
1. Data Collection using yFinance API
2. Data Preprocessing & Feature Engineering
3. Adding Technical Indicators
4. Data Normalization
5. Building Custom Trading Environment
6. Training RL Model (PPO)
7. Model Evaluation
8. Visualization & Performance Analysis

---

## 📊 Output
- Trained RL model (`ppo_stock_trading_model`)
- Processed dataset (`processed_stock_data.csv`)
- Predictions file (`predictions.json`)
- Performance graphs (portfolio value, win rate, etc.)

---

## ▶️ How to Run
```bash
pip install stable-baselines3 shimmy yfinance gymnasium scikit-learn matplotlib
python mini_project.py
