# Treasure Hunt Game -- Deep Q-Learning Agent
### Table of contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Environment Description](#environment-description)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Results](#results)

## Overview
This project implements a Deep Q-Learning (DQN) agent to solve a grid-based Treasure Hunt game. The objective is to train an intelligent agent (the "pirate") to navigate a maze and reach a treasure while avoiding invalid or suboptimal moves. <br><br>
The notebook demonstrates how reinforcement learning can be applied to path-finding problems using neural networks and Q-learning, combining concepts from machine learning, artificial intelligence, and gaming environments. <br><br>
This project was completed as academic coursework and is included in my e-portfolio.

## Problem Statement
Given a maze-like environment: <br>
- The agent starts at a fixed position
- A treasure is located at the goal cell
- The agent can move in four directions
- Some paths are blocked or penalized

The problem is to train an agent that learns the optimal policy for reaching the treasure using **Deep Q-Learning**, rather than hard-coded rules or shortest-path algorithms

## Environment Description
- The environment is represented as a 2D grid (maze)
- Each cell represents a possible state
- The agent receives:
  - Positive reward for reaching the treasure
  - Negative reward for invalid or inefficient moves
- The agent's goal is to maximize cumulative reward

The maze visualization updates dynamically to show:
- Visited cells
- Current agent position
- Final treasure location

## Technologies Used
- Python
- Jupyter Notebook
- Numpy
- Keras (TensorFlow backend)
- Matplotlib
- Reinforcment Learning (DQN)

## Methodology
1. Environment Setup <br>
   The maze and game rules are defined using provided classes. Each state represents the agent's current position within the maze.
2. Deep Q-Learning Model <br>
  A neural network is used to approximate the Q-value function:
    - Input: current state of the maze
    - Output: Q-values for possible actions
  The model is building using Keras with:
    - Fully connected layers
    - Non-linear activation functions
    - Gradient-based optimization
3. Training Process <br>
   The agent is trained using:
     - Exploration vs exploitation strategy
     - Experience replay
     - Iterative updates to the Q-network
   Over time, the agent improves its decision-making by learning which actions lead to higher rewards.

## Results
