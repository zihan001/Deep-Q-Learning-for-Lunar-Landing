# Deep-Q-Learning-for-Lunar-Landing

This repository contains an implementation of a Deep Q-Learning (DQN) agent designed to solve the Gym Lunar Landing v2 environment. The agent utilizes a greedy epsilon strategy for exploration during training.

Overview
========
The implementation uses a Deep Q-Network (DQN) architecture to approximate the Q-values for state-action pairs. It employs an epsilon-greedy strategy to balance exploration and exploitation during training. The model learns to land a lunar module safely by optimizing the reward received based on its actions.

Hyperparameters
===============
* learning_rate
* minibatch_size
* discount_factor
* replay_buffer_size
* interpolation_parameter
