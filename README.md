# Price Optimization

This is a project on price optimization using a simulated demand model to optimize the pricing and profit maximization using reinforcement learning.


# Environment: Complex price response function

Optimizing prices using a traditional methods like using an approximate Statistical distribution as a demand model involves a lot of assumptions which won't hold in the long run. An ML algorithm like LightGBM/XGBoost to predict the demand needs good quality data to get a good price response function.

For the purpose of understanding, a simulated price response function with temporal dependency and a closeness to Black Friday is used to evaluate the efficacy of DQN algorithm

# Baseline model

We can come up with two baseline models to compare with DQN

*   Optimal constant price
*   Optimal price schedule using greedy search 

# Solution: Price Optimization Using DQN
A standalone DQN-based optimizer using PyTorch.

# Observations 

The DQN is able to match the profit obtained from the greedy search

# References
* https://github.com/dennybritz/reinforcement-learning
* https://github.com/ikatsov/tensor-house
