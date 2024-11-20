---
title: "Deep reinforcement learning based UAV positional control under wind disturbance (Course Project)"
excerpt: "<iframe width='420' height='280' src='https://www.youtube.com/embed/7iJJuh3uqDg' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe>"
collection: portfolio
---

<iframe width="420" height="280" src="https://www.youtube.com/embed/7iJJuh3uqDg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This work is using deep reinforcement learning algorithm (TD3) to train an end-to-end positional controller for UAV hover under wind disturbance, it outperforms the SE3 controller, however, in the task of path tracking, RL policy show comparable performance with SE3 controller.    
The improvements include:
* Action history as input of actor net
* cirruculum learning
