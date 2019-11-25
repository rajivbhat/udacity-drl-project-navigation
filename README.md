# udacity-drl-project-navigation
Project submission for Udacity Deep Reinforcement Learning Navigation Project

This project is a solution for the Banana Navigation problem statement. The goal of this project is to train an agent to collect bananas in a square world. There are two kinds of bananas in the two dimensional world. The agent has to avoid the blue bananas while collecting as many yellow bananas as possible. 

Environment:
The agent has to traverse a two dimensional space. The state space is defined with 37 dimensions. The environment is a Unity environment.

Agent: 
The agent is a DQN agent and is in the file agent.py. This agent is identical to the one used to solve the Open AI environment in an earlier exercise. 

Actions:
The agent has four actions available to it - moving forward, moving backward, turning left and turning right.

Rewards:
The agent gets a reward of +1 for collecting a yellow bananas and a penalty of -1 for a collecting a blue banana. 

Goal: 
The agent needs to collect an average score greater than +13 over 100 episodes in order to solve the environment. 


Getting started

This submission has been trained using a Ubuntu Linux 16.04 environment using Python 3 and PyTorch. It uses the Banana_Linux_Novis (headless) environment for training. It uses the drlnd environment that is available as part of the Udacity Deep Reinforcement Learning Nanodegree material. 

Instructions
Clone the git repository. Open Navigation.ipynb in a Jupyter notebook. Ensure that the Banana_Linux_NoVis directory is in the same location as the notebook. Also ensure that the notebook is using the drlnd environment. Execute the cells in sequence to solve the environment. 

