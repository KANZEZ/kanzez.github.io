---
title: "Risk-Aware Multi-Robot Target Tracking with Dangerous Zones (Personal Project)"
excerpt: "<iframe width='420' height='280' src='https://www.youtube.com/embed/2ES891q0BQo' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe>"
collection: portfolio
---

<iframe width="420" height="280" src="https://www.youtube.com/embed/2ES891q0BQo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This work in a partial code reproduction for paper:     
[Risk-Aware Multi-Robot Target Tracking with Dangerous Zones](https://ippc-iros23.github.io/papers/liu.pdf)

Multi-robot target tracking is the problem of
actively planning the motion of a team of coordinating robots
such that they can track and follow the targets. Traditional
approaches often focus solely on optimizing the tracking accuracy, neglecting potential environmental hazards that can induce system faults such as sensor or communication failures on the robots. In this paper, we focus on solving multi-robot target tracking in an adversarial environment with two types
of dangerous zones—sensing danger zone and communication
danger zone. Robots’ sensors are at the risk of being damaged
if robots are in the sensing danger zone, while inter-robot
communication signals can be jammed if robots are in the
communication danger zone. The positions of both types of
zones are uncertain and assumed to follow a Gaussian distribution. We model the risk of attack in dangerous zones as probabilistic constraints, and propose an optimization program
that optimizes the tracking performance while ensuring robots’
safety through such constraints. The probabilistic constraints
are linearly approximated so that the optimization program
becomes tractable. We demonstrate the efficacy of the proposed
approach through extensive simulations.
