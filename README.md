# RL-Options-Trading-Strangle-Strategy
This repository contains a Reinforcement Learning (RL) model designed to apply the Strangle options trading strategy using Deep Q-Networks (DQN). The model is developed to handle categorical data and technical indicators, making it suitable for real-time trading scenarios.

#Project Overview

The StrangleTradingEnv simulates an options trading environment where a reinforcement learning agent can learn to make profitable trades based on historical options data. The environment rewards the agent for successful trades and penalizes it for losses, aiming to optimize the trading strategy over time.

#Features
Custom Trading Environment: Built on top of OpenAI's Gym interface, it includes features like dynamic reward systems and customized action spaces.
Reinforcement Learning Model: Utilizes a DQN model to learn the trading strategy.
Technical Indicator Integration: Uses various technical indicators such as RSI, MACD, and Bollinger Bands to make informed trading decisions.
Performance Metrics: Evaluates the trading strategy using metrics like total profit, Sharpe ratio, and maximum drawdown.

#Installation
To set up this project, clone the repo and install the required packages:

