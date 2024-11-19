---
title: "Safe Interval Motion Planning for Quadrotor in Dynamic Environments (Research Project)"
excerpt: "<iframe width='420' height='280' src='https://www.youtube.com/embed/Bx_q_11eOrg' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe>"
collection: portfolio
---

<iframe width="420" height="280" src="https://www.youtube.com/embed/Bx_q_11eOrg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Trajectory generation in dynamic environments is a challenging problem in motion planning. Existing work often assumes static environments, or fails to find optimal solutions online due to the highly non-convex nature of the environment. In this work, we propose an efficient safe interval motion planning framework for navigation in dynamic environments. Our approach addresses trajectory generation through a two-stage process: a front-end graph search step followed by a back-end gradient-based optimization. We ensure completeness and optimality by constructing a dynamic connected visibility graph and incorporating low-order dynamic bounds within safe
intervals and temporal corridors. To avoid local minima, we propose a Uniform Temporal Visibility Deformation (UTVD) for the complete evaluation of spatial-temporal topological equivalence. We represent trajectories with B-Spline curves and apply gradient-based optimization to navigate around static and moving obstacles within spatial-temporal corridors. Through
simulation and real-world experiments, we show that our method can achieve a success rate of over 95% in environments with different density levels, exceeding the performance of other approaches, demonstrating its potential for practical deployment in highly dynamic environments.
