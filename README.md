# RL-Collect-all-Bananas

## Introduction

This project aims at training an agent to navigate and collect bananas.
Rules are the following:
- Reward = +1 for each yellow banana collected
- Reward = -1 for each blue ones (Thus the goal is to collect as many yellow bananas as possible while avoiding collecting blue ones).

The state space is a 37 dimensions space which contains the agent's velocity along with a ray-based perception of objects around agent's forward direction.

Four actions are available:

- 0 : move forward.
- 1 : move backward.
- 2 : move left.
- 3 : move right.

In order to be considered "Resolved" the agent must get an average score of +13 over 100 consecutives episodes (the task is episodic).

## Installation

Follow the instructions on this [repo](https://github.com/udacity/deep-reinforcement-learning#dependencies) to install all the dependencies
Note that if you are running the code on Windows you might have trouble installing the box2d environnement you can solve this issue by using `pip install box2d` instead of `pip install gym[box2d]`.

Then follow the instructions on this [section](https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md#getting-started).

## What contains this Repository ?

- A notebook containing the code to train an agent to solve the task.
- A .py file containing the architecture for a DQN Agent and a DDQN Agent.
- A .pth file containing the weights of an agent that solved the task (DQN and DDQN).
- A report describing the architecture and the hyperparameters used to solve the task.
