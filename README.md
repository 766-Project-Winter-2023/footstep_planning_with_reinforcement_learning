# Footstep_Planning_with_Reinforcement_Learning
footstep_planning program in Unity with different steering algorithms.

Pengxiang Jia, Yide Ma

This is a novel implementation of paper: [Footstep navigation for dynamic crowds](https://people.cs.rutgers.edu/~mk1353/pdfs/footstep-navigation.pdf).
We have utilize different rl algorithm to train the footstep model.

# Environments: 
!conda create -n xxx python=3.9
!conda activate xxx
!pip install mlagent==0.30.0
#also install cuda and pytorch in your environments
#i used cuda 11.6 and pytorch 1.12.1
#unity version we use: 2019.4.29f1
#ml-agent version in unity editor i used is 2.0

# Running
make sure the pretrain model is in the nn module for body, then play

# Training
if you want to play around with training, use the command below:
!mlagents-learn C:\Users\xxx\OneDrive\Desktop\FootstepAgents\Config\MyBehavior.yaml --run-id=MyBehavior --force

# Result of using ppo network


