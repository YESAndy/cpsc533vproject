## Welcome to Our Project

You can use the [editor on GitHub](https://github.com/YESAndy/cpsc533vproject/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.https://jekyllrb.com/docs/usage/

This page will showcase results from our experiments.

### Overview of the experiments

Our experiments considered the design of state that may affect the performance of the algorithm. There are two different state designs: 1)state1: 15 dimensions, including the 6-dimensional joint position and 9-dimensional gripper’s velocity, position, and rotation; 2) state2: 9 dimensions consisting of the gripper's velocity, position, and rotation.

### Graphs
time step vs cumulative reward for each experiment. The blue line is for agent with state1. the orange line is for agent with state2.
![]()

time step vs episode length.
![]()

time step vs value loss
![]()

time step vs policy loss
![]()

time step vs policy entropy
![]()


![]()
![]()


### Videos
The inference results for the trained agent with state1
<img src="https://github.com/YESAndy/cpsc533vproject/blob/main/ppo_nr_e0.05_s2.gif" width="600" height="400" />

The inference results for the trained agent with state2
<img src="https://github.com/YESAndy/cpsc533vproject/blob/main/ppo_nr_e0.05_s2.gif" width="600" height="400" />


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
