# Deep Q-Network for Banana Navigation Environment

## Environment
This project utilizes the Unityu ML agent Banana environment to build a reinforcement learning agent. The agent is built using a deep Q-network, with the objective of only collecting yellow bananas, not blue ones. The agent is rewarded accordingly (+1 points for yellow bananas and -1 for blue).

The state space has 37 dimensions including velocity and ray-based perception of objects relative to the agent's forward direction. The agent can select from 4 possible actions (forward, backward, left and right).

The environment is considered solved when the agent obtains an average score of +13 over 100 consecutive episodes for this episodic task.

## Requirements
(1) Clone this repository

(2) To get your python environment setup, follow the instructions at the following link: https://github.com/udacity/deep-reinforcement-learning#dependencies. You will be guided into installing PyTorch, the Unity ML-Agents Toolkit and some additional required python packages.

(3) Download the Unity environment and place it in the directory where you cloned this repo. Below are links, pick only one based on which operating system you're running.
* Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
* Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip
* Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip
* Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip

## Running the Agent
(1) Open jupyter lab or jupyter notebook in the cloned directory
(2) The file "Navigation_Solution.ipynb" contains all the code you need to run to train an view the agent
(3) The file "dgn_agent.py" defines the Deep Q-Network agent (no need to open)
(4) The file "model.py" defines the deep neural network used to train the agent (no need to open)
(5) The file "checkpoint_navDQN.pth" contains the weights of the trained agent (no need to open)



