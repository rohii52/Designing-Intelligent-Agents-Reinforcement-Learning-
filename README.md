# Designing Intelligent Agents: Reinforcement Learning and Dynamic Programming

This repository contains coursework for COMP4105 - Designing Intelligent Agents. It explores dynamic programming (DP) and reinforcement learning (RL) techniques to solve sequential decision-making problems. These methods include value iteration, policy iteration, and Bellman Equations to compute optimal policies and values for agents in various environments.

---

## Overview

Dynamic programming and reinforcement learning provide computational strategies for solving decision-making problems over time. These methods have applications across domains like automatic control, artificial intelligence, economics, and operations research. This repository implements key RL techniques and showcases their practical application through classical problems like Jack's Car Rental, Gambler's Problem, and Gridworld.

---

## Repository Structure

- **Gambler's Problem**:
  - Implementation of value iteration to determine the optimal betting strategy.
  - Files:
    - `Gambler's_Problem.ipynb`
    - Output: `gambler_problem_plot.png`
  
- **Gridworld Problem**:
  - Evaluation of equiprobable random policies in a small 4x4 Gridworld.
  - Files:
    - `Gridworld_Problem.ipynb`
    - Output: `grid_world_plot.png`
  
- **Jack's Car Rental Problem**:
  - Demonstrates policy iteration to maximize rewards from car rentals.
  - Files:
    - `Jack_Car_Rental_Problem.ipynb`
    - Policy and state plots for different iterations.
  
- **README.md**:
  - This document provides a comprehensive overview of the project.

---

## Key Concepts

### 1. **Dynamic Programming (DP)**
DP is used for planning in Markov Decision Processes (MDPs). It solves:
- **Prediction Problems (Policy Evaluation)**:
  - Calculates the value function of a given policy using the Bellman Expectation Equation.
- **Control Problems**:
  - Derives the optimal policy using the Bellman Optimality Equation.

### 2. **Reinforcement Learning (RL)**
RL is ideal for situations where the system model is unavailable. Key approaches include:
- **Model-Based RL**: Relies on predefined system dynamics.
- **Model-Free RL**: Learns from interactions with the environment (e.g., Q-Learning).

### 3. **Bellman Equations**
- Core mathematical framework for solving MDPs.
- Iteratively updates value functions to achieve convergence.

---

## Implemented Problems

### Jack’s Car Rental Problem
Jack manages two locations for a rental company. The problem involves:
- Maximizing rental revenue by redistributing cars overnight.
- Solving with Policy Iteration using Bellman updates.

### Gambler’s Problem
The agent bets on coin flips with a 40% chance of winning. The objective:
- Derive an optimal policy for maximizing capital using Value Iteration.

### Gridworld Problem
A 4x4 grid environment where:
- The agent follows a random equiprobable policy.
- Evaluates policy performance through iterative updates.

---

## Results

1. **Convergence and Optimization**:
   - Value and policy iteration methods converge to optimal solutions across different problems.
   
2. **Challenges Addressed**:
   - Handling discrete state spaces effectively.
   - Balancing computational complexity with accuracy.

3. **Policy Evaluation**:
   - Iterative improvement of policies demonstrates efficient decision-making.

---

## Limitations & Future Work

### Limitations:
- Computational scalability in continuous state/action spaces.
- Dependency on accurate environment dynamics for model-based methods.

### Future Directions:
- Explore hybrid approaches combining model-free and model-based RL.
- Apply deep reinforcement learning techniques for function approximation in high-dimensional spaces.

---

## Getting Started

### Prerequisites
- Python 3.8+
- Required libraries: `numpy`, `matplotlib`, `seaborn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rohii52/Designing-Intelligent-Agents-Reinforcement-Learning.git
