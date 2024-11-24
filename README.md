# Reinforcement Learning Assignments
Authors: Enzo Benoit-jeannin and Sasha Denouvilliez-Pech 

This repository contains three Jupyter Notebooks detailing experiments and analysis performed as part of our reinforcement learning coursework. Each Jupyter Notebook contains in-depth code, results, and analysis for the algorithms implemented. For detailed information and results, please refer to the individual notebooks. Below is an overview of each assignment.

## Assignment 1

**Algorithm Implemented**: Bandit Algorithms

**Description**: This assignment involves experiments with Bernoulli bandit algorithms to understand and practice reinforcement learning concepts discussed in class. It includes implementing a small simulator for a Bernoulli bandit with multiple arms, coding the rules for estimating action values, and running extensive experiments to compare different estimation strategies including fixed learning rates and the ε-greedy algorithm. Additional experiments use the Upper Confidence Bound (UCB) and Thompson sampling methods.

**Key Experiments**:
- Test Bernoulli bandit with varying probabilities.
- Implement and compare fixed learning rates and ε-greedy strategies.
- Advanced strategies: UCB and Thompson sampling in both stationary and non-stationary settings.

## Assignment 2

**Algorithms Implemented**: SARSA and Expected SARSA

**Description**: This assignment compares SARSA and Expected SARSA on the Taxi Problem from the Gym environment suite. It tests different temperatures and learning rates for the softmax exploration method, measuring the return over time and providing a detailed analysis of the training and testing performance.

**Key Experiments**:
- Compare SARSA and Expected SARSA using softmax exploration.
- Analyze the impact of temperature and learning rate on performance.
- 
## Assignment 3

**Algorithms Implemented**: Q-Learning, Expected SARSA, REINFORCE and Actor-Critic methods

**Description**: Implements Q-Learning and Expected SARSA for both the MountainCar-v0 and CartPole-v1 environments using linear function approximation. It also covers policy-based methods with the REINFORCE and Actor-Critic methods, exploring different configurations of learning rates and temperature settings.

**Key Experiments**:
- Plot the average performance of the policy as a function of the number of episodes foir both Q-Learning and Expected SARSA on both environments and comapred them.
- Perform the same experiemnt comparing REINFORCE and Actor-Critic methods.

