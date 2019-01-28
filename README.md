# DQN

This project allows an agent to learn how to play OpenAI's LunarLander-V2 using deep Q-learning.
The neural networks were created using Pytorch.The agent utilizes neural network for Q function a
pproximating and another neural network as the target value to try to solve the issue with moving Q-targets.
The game was considered solved at 200 points but I allowed the agent to continue training until the average
of the past 100 episodes was above 235 points just to be sure as there was some oscillation between scores.
So it finished training at episode 508.

![Alt text](https://github.com/ethsu1/DQN/blob/master/Screen%20Shot%202019-01-27%20at%2011.28.27%20PM.png)
![Alt text](https://github.com/ethsu1/DQN/blob/master/dqnclip.gif)
