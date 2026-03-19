---
layout: archive
title: "Seismic moment"
permalink: /general/moment
author_profile: true
mathjax: true
---

{% include base_path %}

## Moment tensor matrix
We can understand the moment tensor matrix through comparing it with the stress tensor. The moment tensor actually describes the deformation at the source 
![moment tensor figure](moment/stress-and-moment-tensors.png)

## How it relates to beachball
More commonly used representation of focal mechanisms is the seismic beachballs. Initially, people obtain the beachball through the direction of P wave first arrivals observed in stations. If an earthquake happens, we treat its location as the origion and build spherical coordinates. The stations are located at an azimuth with respect to this event, and we can use $(\theta, \phi)$ to discribe the azimuth of stations. If we observe a positive P-wave first arrival, we plot a black dot there and a white dot vice versa. People found that the entire sphere is devided into four parts with two postive(black, representing tension) and two negative(white, representing compression). The two deviding planes are orthogonal to each other, If we project the southern hemisphere to a circle using the equalarea projection($r = cos(\theta), \phi = \phi$), we obtain the beachball. 

![beachball](moment/p-and-s-beach-balls.png)

It is also feasible to build a bridge between the beachball representation and the moment tensor matrix. If we want to know whether a point on the beachball, quantified by $(\theta, \phi)$ is positive or negative, we can calculate it as $n^T M n$ with $n = (sin\theta cos\phi, sin\theta sin \phi, cos\theta)^T$ and $M$ the moment tensor matrix. Therefore, I think the beach ball can probably be better represented with not only positive or negative, but also the exact value. 

## Source time function


## How to simulate the displacement function observed in one station?


[1] https://mxrap.com/theory/moment-tensor-guide/