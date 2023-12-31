# Project-Continuous-Control---DRL

A project for training a double-jointed arm be able to reach target locations using the Unity Environment
## Project Description
[//]: # (Image References)

[image1]: https://video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif "Trained Agent"

![Trained Agent][image1]

In the simulated environment, a reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

For this project, there are two separate versions of the Unity environment:
- The first version contains a single agent.
- The second version contains 20 identical agents, each with its own copy of the environment. 

In order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.
## Getting Started

1. Download the entire repository and unzip (or decompress) the python.zip

2. Place the "python" folder in the working folder.

3. Follow the instructions in `Continuous_Control.ipynb` to get started with training the agent! You can try tuning the hyperparameter as well!

4. You can also load the pretrained model weight provided to see how the agents work.

## Visualizing Results

The environment was solved in 119 episodes with	Average Score is 30.16

![plot](scores.png)
