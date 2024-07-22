---
title: "Push Recovery for Humanoid Robots using Linearized Double Inverted Pendulum"
collection: ProQuest
permalink: /publication/2020_MSThesis
excerpt: 'This paper presents a novel balance control scheme using a Linearized Double Inverted Pendulum model to enhance a humanoid robot's recovery from external disturbances, validated on the simulated TigerBot-VII.'
date: 2020-06-07
venue: 'ProQuest'
paperurl: 'http://sauravsingh1245.github.io/files/2020_MSThesis.pdf'
citation: 'L. Nagahanumaiah, S. Singh and J. Heard, “Diagnostic Human Fatigue Classification using Wearable Sensors for Intelligent Systems,” 2022
17th Annual System of Systems Engineering Conference (SOSE), 2022, pp. 424-429.'
---
Biped robots have come a long way in imitating a human being's anatomy and posture. Standing balance and push recovery are some of the biggest challenges for such robots. This work presents a novel balance control scheme for a humanoid robot to recover from external disturbances. The proposed Linearized Double Inverted Pendulum, models the dynamics of a complex humanoid robot. The joint torque signals are generated along with ankle torque constraints to ensure the Center of Pressure stays within the support polygon. Simulation results show that the presented model can successfully recover from external disturbances while using minimal effort when compared to other widely used simplified models. It optimally uses the the torso weight to generate angular moment of inertia about the pelvis of the robot to counter-balance the effects of external disturbances. The proposed method was validated on simulated TigerBot-VII, a humanoid robot.
![Linearized Double Inverted Pendulum Model.](\../images/LDIP-robot.png)
![Gazebo simulation response with constrained LQR on LDIP model to an impulsive disturbances that changes velocity of pelvis from rest to 0.35m/s.](\../images/Gazebo_sim_horizontal.png)