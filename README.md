Udacity Continuous Control Project

1. Project Overview

This project is part of the Udacity Deep Reinforcement Learning nanodegree, aiming to solve the Reacher environment. The goal is to train an agent to control a double-jointed arm to reach target locations, with a reward of +0.1 for each step the agent's hand is in the goal location. The agent's objective is to maintain its position at the target location for as many time steps as possible.

2. Environment Details

The observation space consists of 33 variables, including position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints, with values between -1 and 1. The environment is considered solved if a reward of +100 is obtained for 30 consecutive episodes.

3. Methodology

The project employs the Deep Deterministic Policy Gradients (DDPG) algorithm, an actor-critic method, to solve the Reacher environment.

4. Getting Started

To begin, follow these steps:

- Set up your Python environment: Follow this link to ensure correct setup.

- Download the Unity Environment: Choose the appropriate link for your operating system:

Linux: Reacher_Linux.zip
OSX: Reacher.app.zip
Microsoft 32 bits: Reacher_Windows_x86.zip
Microsoft 64 bits: Reacher_Windows_x86_64.zip (For Windows users, check this link to determine your operating system's bit version.)
- Place and unzip the file: Place the downloaded file in the p2_continuous-control/ folder in the DRLND GitHub repository and unzip (or decompress) the file.

- Run the training: The training can be run directly in the notebook.