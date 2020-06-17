# Project 1: Navigation
## Introduction
#### The Unity environment
In this project we are solving the "Tennis" environment using the open-source Unity plugin **Unity Machine Learning Agents (ML-Agents)**. The main use-case of those environments is to use trained agents for multiple purposes. But we are using it for designing, training and evaluating the performance of our own agent. 
#### The game and the rewards
The goal in the environment "Tennis" is to keep the ball in play by the two rackets. This goal is definined by the reward rule +0.1 for hitting the ball over the net and -0.01 for hitting the ball out of bounds or letting the ball hit the ground. 
![Tennis example](https://video.udacity-data.com/topher/2018/May/5af7955a_tennis/tennis.png)
#### The action and state space
The continuous action space is a 2-dimensional vector, each entry between -1 and 1 and corresponding to the movement towards or away from the net, and jumping. The state space consists of three frames of the position and velocity of the ball and racket. Each frame has 8 dimensions which makes the state-space 24-dimensional.
#### The action and state space
The continuous action space is a 2-dimensional vector, each entry between -1 and 1 and corresponding to the movement towards or away from the net, and jumping. The state space consists of three frames of the position and velocity of the ball and racket. Each frame has 8 dimensions which makes the state-space 24-dimensional.
#### The instructions for solving the environment
The environment is considered to be solved after having achieved an average score of 0.5 in 100 consecutive episodes. 
#### The instructions for installing the environment
1. Clone the repository https://github.com/fjonck/Project_3_Collaboration_and_Competition
2. Open the notebook Tennis.ipynb with Jupyter Notebook
3. In the menu, click on Cell -> Run All
4. Enjoy watching the Tennis Agent learn :)
