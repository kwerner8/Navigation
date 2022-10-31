# Project 1: Navigation


## Description of the implementation

### Algorithms
In order to solve this challenge, I have implemented a [Deep Q-Network](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf) algorithm. In future investigations more sophisticated deep reinforcement learning algorithms can be investigated, such as:

* [Double Deep Q-Network](https://arxiv.org/abs/1509.06461)
* [Dueling Q-Network](https://arxiv.org/abs/1511.06581)
* [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)

##### Deep Q-Network
I began this project by implementing a Deep Q-Network (DQN) using Experience Replay and Fixed Q-Targets. The goal for this project was getting a reward of +13 over 100 episodes. In my first attempt, I built a DQN with **2 fully-connected (FC) layers, 64 nodes each one**. This model solved the environment in 570 episodes.

Then, I increased the number of nodes in the first layer to 80. I also decreased the learning rate from 5e-4 to 3e-4. This architecture solved the environment in 369 episodes.
 


## Ideas for Future Work
Negative rewards could be introduced to discourage the agent from arbitrarily moving away from its goal of searching for yellow bananas.

There are other algorithms that have been proposed to improve the performance of the Deep Q network. In a future work, these could be implemented to verify their performance in this environment. These algorithms are:
   * [A3C - Asynchronous advantage actor-critic](https://arxiv.org/abs/1602.01783)  
   * [Noisy DQN](https://arxiv.org/abs/1706.10295)  
   * [Distributional DQN](https://arxiv.org/abs/1707.06887)  


