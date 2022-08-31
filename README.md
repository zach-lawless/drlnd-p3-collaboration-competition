# drlnd-p3-collaboration-competition
Udacity Deep Reinforcement Learning Nanodegree Project 3 repository

## Project Details
The goal of this project is to train two agents to play tennis in a collaborative manner.

The state space for this environment consists of 24 variables for each agent in the environment, and when concatenated together for training, the input environment representation is of size 48.

The action space for each agent is a vector of length 2. The values are continous actions indicating movement towards or away from the net, and jumping.

The environment is considered solved when the agents receive an average reward of 0.5 for the last 100 episodes.

## Getting Started
The easiest way to run this repository would be to clone it into an existing Udacity virtual workspace. This is because the Python requirements and install instructions in the Udacity DRLND Github repository is rather outdated, and the virtual workspaces provided already contain everything needed for execution. All development for this project was completed on the Udacity virtual workspace.

If it's desired to run this agent locally, clone the [DRLND Github repo](https://github.com/udacity/deep-reinforcement-learning/) and follow the setup instructions for the whole repository. From there, follow the project-specific instructions located under `p2_continuous_control`.

## Instructions
In order to train the agent, run `Tennis.ipynb` end-to-end. More details on each individual cell and the purpose are provided inside the notebook.
