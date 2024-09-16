# FrozenLake Q-Learning

This project implements a Q-learning algorithm to solve the FrozenLake-v1 environment from OpenAI's Gymnasium. The agent is trained to navigate a 4x4 grid of ice to reach the goal while avoiding holes, using a model-free reinforcement learning approach.

## Overview

- **Environment**: FrozenLake-v1 (4x4 map, deterministic movements)
- **Algorithm**: Q-learning with epsilon-greedy exploration
- **Training Output**: A Q-table that learns the optimal actions for each state
- **Visualization**: Training and testing results are saved as gifs (`training.png` and `test.png`)

The agent learns through multiple episodes by interacting with the environment, updating its Q-table based on rewards and future expectations. After training, it navigates the frozen lake efficiently by following the optimal learned policy.
