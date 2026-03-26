---
layout: archive
title: "RSQSim simulations"
permalink: /general/rsqsim
author_profile: true
mathjax: true
---

{% include base_path %}

This page should contain    
(i) the three stages in RSQSim    
(ii) the transfer condition between stages, or how the system evolves   
(iii) the background in some approximations, including overshoot, decreasing a, no stress change caused by nucleation

## three stages
### 0 (healing)
$$\theta$$: $$d\theta / dt = 1$$ 
leads to the solution $$\theta = \theta_0 + t$$
velocity is close to 0 and neglecable
stress increases
### 1 (nucleation)
$$\theta$$: $$d\theta / dt = -V\theta / D_c$$
velocity is expected to grow exponentialy with time
(a figure illustrating how the velocity evolves with time)
### 2 (seismic rupture)
fixed velocity at $$V_{eq}$$
stress drops to the steady state stess considering overshoot
state decreases as well

## transfer criterion
### 0 -> 1
this element enters the steady-state line
### 1 -> 2
velocity reaches $$V_{eq}$$
### 2 -> 0
stress decreases to the overshoot term

## tricks
### a decrease in a/b

### overshoot stress