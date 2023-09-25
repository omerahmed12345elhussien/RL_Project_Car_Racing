# Implementation of Deep Q-Learning (DQN), Double DQN, and Actor-Critic policy Gradient for Car-Racing_v0 game

In this project, we are interested in training the DQN and A2C agents on [Car-Racing_v0](https://gymnasium.farama.org/environments/box2d/car_racing/) environment.  The Car-Racing environment is part of the [Box2D](https://gymnasium.farama.org/environments/box2d/) environments. 

In the video below, we present samples of interactions with the environment.

<img width="300" height="300" alt="color picker" src="https://github.com/omerahmed12345elhussien/RL_Project_Car_Racing/blob/omer/added-files/GIFs/DQN/animation_interaction.gif" />

## DQN and DDQN

[Q-learning](https://www.nature.com/articles/nature14236) is a value-based reinforcement learning algorithm used to find the optimal policy for an MDP. It operates by iteratively updating a Q-table, where each entry (Q-value) represents the expected cumulative reward of taking a specific action in a specific state. The iterative process involves the agent learning by exploring the environment and updating the model as the exploration continues.

[Double Deep Q-Learning (DDQN)](https://arxiv.org/abs/1509.06461) is an enhancement of the classic Q-learning algorithm. It addresses the issue of overestimation bias in Q-values by using two separate Q-value networks: an online network and a target network. DDQN employs experience replay to improve sample efficiency and stabilize training.

[![Click here to open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/omerahmed12345elhussien/RL_Project_Car_Racing/blob/omer%2Fadded-files/DQN_notebook.ipynb)

## Actor-Critic (A2C)
