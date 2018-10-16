
# Learning Algorithm

The algorithm for the agent is [DQN](https://arxiv.org/pdf/1312.5602.pdf)

model.py file contains neural network definition
dqn_agent.py file implements Agent and ReplayBuffer classes

Hyperparameters:

Network architecture:


# Plot of Rewards

A plot of rewards per episode is included to illustrate that the agent is able to receive an average reward (over 100 episodes) of at least +13. The submission reports the number of episodes needed to solve the environment.

!(Rewards per episode)[rewards_per_episode.png]

# Ideas for Future Work

* I would like to use [Tensorboard for PyTorch](https://github.com/lanpa/tensorboardX)
* I would like to spend some time and train an agent from raw pixels
* I would like to spend some time and compare the performance of the agent to [Double DQN](https://arxiv.org/abs/1509.06461) and [Dueling DQN](https://arxiv.org/abs/1511.06581)
* I'm also interested exploring [Rainbow: Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/abs/1710.02298)
* Also, a colleague of mine is learning Unity and created a simple game, I'd like to apply what I learned and solve this gave using RL
