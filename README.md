# QuadCopter - Reinforcement Learning
Udacity Machine Learning - Advanced Nanodegree - Quadcopter

This was a very difficult project using Reinforcement Learning.
The task was to take off the quadcopter to a target height.

# Agent:
Designed an agent using actor-critique algorithm. 
Neural network architecture was designed for Actor Class, Critic Class (State and Action)

# Task:
An appropriate reward function was designed after several hours of fine tuning:
The final reward function is :
If current position is below target, reward is the current position. So lower current position, lower reward.
If current position is above target, reward is double the target position - current position. So the higher it goes , lesser is the reward.
If current position = target position , reward is highest = target position.

# Final Result:
After fine tuning of the hyper parameters, the agent was trained successfully.
Also the z position value went up to the target level successfully.

Proud to have achieved the result. Check the details in Quadcopter_Project.ipynb
