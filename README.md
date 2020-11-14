# Tennis Collaboration/Competition Project



## Introduction
In this project 2 agents will be trained to play tennis. Each agent recieves 0.1 reward for every time that the agent is able to hit the ball over the net and not out of bounds. If the ball goes out of band or the agent let the ball hit the ground the agent recieves a reward of -0.01.

The observation space space consists of 24 different states for each agent which consists of position and velocity of the ball and the racket. For the action space there are two continous actions between -1 and +1 that corresponds to moving back and forth and jumping.

In the below image we can see a snaphot of the enviroment with the two agents playing tennis.
![image](https://github.com/erab17/RL_Tennis_MA/blob/main/image.png)

The target for the project is to achieve a mean rolling reward over 100 episodes of 0.5 or more of the maximum of one agents score during an episode.

## Getting Started
1. For setting up the python environment follow the instructions in this link:
https://github.com/udacity/deep-reinforcement-learning#dependencies

2. Download the environment from one of the links below. You need only select the environment that matches your operating system:

* Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
* Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
* Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
* Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

3. Place the file in the repo.

4. The following libraries need to be installed and imported in order to run all the cells in the notebook
* UnityEnvironment from unityagents  
* numpy  
* random  
* namedtuple and deque from collections  
* torch  
* matplotlib
* import pickle
* pandas
* copy

## Instructions
To run the agent in the environment and using the different methods one just have to sequantially execute the cells in the notebook. The notebook can be opened with vscode, jupyter lab or jupyter notebook.

The algorithm will for about 2300 episodes with the current settings.

Files in the repo:
* Tennis.ipynb (Notebook for running and training the agents)
* checkpoint_actor_0.pth (Saved weights for agent 1's actor network)
* checkpoint_actor_1.pth (Saved weights for agent 2's actor network)
* checkpoint_critic_0.pth (Saved weights for agent 1's critic network)
* checkpoint_critic_1.pth (Saved weights for agent 2's critic  network)
* file.pkl (Saved scores per episode and rolling score)


