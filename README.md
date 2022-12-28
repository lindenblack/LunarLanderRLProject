# LunarLanderRLProject
### One Small Step for Man - One Giant Leap for Reinforcement Learning
### An Investigation of Modern Deep Reinforcement Learning Algorithms Using the Lunar Lander Open AI Gym Environment

![alt text](https://wingedsheep.com/content/images/2020/08/lunarlanderpost-2.png)

#### Introduction
In this project I train and compare four different RL methods using the OpenAI Gym Discrete Lunar Lander environment. 

#### The environment 
https://github.com/openai/gym/blob/master/gym/envs/box2d/lunar_lander.py

The state of the environment is described by:
- x coordinate
- y coordinate
- x velocity
- y velocity
- lander angle
- lander angular velocity
- leg 1 angular contact
- leg 2 angular contact

The actions inlude:
- do nothing
- fire left orientation engine
- fire main engine
- fire right orientation engine

#### The models
I trained four deep reinforcement learning models, Advantage Actor Critic (A2C), Proximal Policy Optimisation (PPO) and two Deep Q-Networks (DQN), one of which is built was self-built using Keras. 
The other models were out of the box from the Stable Baselines library. 
