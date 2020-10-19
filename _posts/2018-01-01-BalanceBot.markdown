---
layout: post
title:  "BalanceBot"
date:   2018-01-01 00:00:01
author: Paul List
categories: Demo
---

A self-balancing inverted pendulum robot remotely-controlled to complete various tasks. Here is a video of the robot drag racing down a hallway and stopping within one meter.

<iframe width="560" height="315" src="https://www.youtube.com/embed/icoMt7SklTc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>





Two types of controllers were demonstrated: PID with successive loop closure, and full state feedback with LQR.
<!---
For PID, the inner loop was used for the angle of the robot, and the outer loop was used for the wheel angle. <br>
Transfer functions - G(s) and D(z) <br>
Block Diagram
<br>
<br>
LQR - State space representation, continuous and discretized.<br>
Q and R matrices<br>
Block diagram
<br>
Gyro, odometry
-->
