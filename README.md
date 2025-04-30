# Shortest Path Finding in Dynamic Graphs using Reinforcement Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)

## Overview

This repository implements and evaluates reinforcement learning approaches for finding shortest paths in dynamic graphs, where edge weights change over time. We compare Q-Learning, Expanded Action Space Q-Learning, and Deep Q-Networks (DQN) against the D* Lite algorithm.

## Authors

- Krishna Sharma, Pratik Rana, Rahul Kumar
- Computer Science and Artificial Intelligence, Plaksha University, Punjab, India

## Key Features

- **Standard Q-Learning** with adaptive training episodes based on graph size
- **Expanded Action Space Q-Learning** allowing non-neighbor moves with penalties
- **Deep Q-Networks** for improved scalability on larger graphs
- **Dynamic environment** simulation with time-varying edge weights
- Performance comparison with **D* Lite algorithm**

## Results Highlights

- RL methods demonstrate significantly faster inference times compared to D* Lite's replanning
- Trade-off between path optimality and execution speed clearly established
- DQN shows promising scalability for larger graphs



## Requirements

- Python 3.7+
- NumPy
- PyTorch
- Matplotlib
- NetworkX

## Project Structure

```
.
├── Plots/              # Contains separate folders for each method's visualization results
├── Code/               # Jupyter notebooks for implementing algorithms and generating results
└── Report.pdf          # Detailed analysis and findings of the research
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
