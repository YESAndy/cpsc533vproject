## Welcome to Our Project

This page will showcase results from our experiments.

### 1 Overview of the experiments

Our experiments considered the design of state that may affect the performance of the algorithm. There are two different state designs: 1)state1: 15 dimensions, including the 6-dimensional joint position and 9-dimensional gripper’s velocity, position, and rotation; 2) state2: 9 dimensions consisting of the gripper's velocity, position, and rotation.

### 2 Graphs
#### 2.1 time step vs cumulative reward for each experiment. The blue line is for agent with state1. the orange line is for agent with state2.
![](https://github.com/YESAndy/cpsc533vproject/blob/gh-pages/Environment_Cumulative%20Reward.png)

#### 2.2 time step vs episode length.
![](https://github.com/YESAndy/cpsc533vproject/blob/gh-pages/episode%20length.png)

#### 2.3 time step vs value loss
![](https://github.com/YESAndy/cpsc533vproject/blob/gh-pages/loss%20value%20loss.png)

#### 2.4 time step vs policy loss
![](https://github.com/YESAndy/cpsc533vproject/blob/gh-pages/loss%20policy%20loss.png)

#### 2.5 time step vs policy entropy
![](https://github.com/YESAndy/cpsc533vproject/blob/gh-pages/loss%20value%20loss.png)


![]()
![]()


### 3 Videos
#### 3.1 The inference results for the trained agent with state1
<img src="https://github.com/YESAndy/cpsc533vproject/blob/gh-pages/ppo_nr_e0.5_s1.gif" width="600" height="400" />

#### 3.2 The inference results for the trained agent with state2
<img src="https://github.com/YESAndy/cpsc533vproject/blob/gh-pages/ppo_nr_e0.5_s2.gif" width="600" height="400" />


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
