[//]: # (Image References)

# Continuous Control - Readme

### Introduction & goal of the project

This is the second project of the [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) by Udacity.
The objective of this project is to train 20 agents with double-jointed arms, that can move to target locations. It's a Unity environment provided by Udacity.  

![Training results](./reacher.gif  "Training results")

The state space has 33 dimensions for each agent and contains the position, rotation, velocity, and angular velocities of the arms.  Given this information, the agent has to learn how to best select actions.  Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.

A reward of +0.1 is provided for each step that the agent's hand is in the goal location.  Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible. 

### Settings

**Implementation:** The project is implemented in `python 3.6` and within a `jupyter notebook`. 

**`Pytorch 1.4.0`** has been used with **`CUDAToolkit 10.1`**.
The operating system is `ubuntu 18.04`.
Unity 2019.3 has been installed on the computer.
The Unity environment is `Banana_Linux/Banana.x86_64` and has been provided by Udacity. 

**Train the agent by executing the whole jupyter notebook from the beginning to the end**