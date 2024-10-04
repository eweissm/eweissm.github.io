---
title: "Academic Projects"
excerpt: "Time evolution of chemical species within the mixing chamber https://github.com/user-attachments/assets/e5122afc-831d-4cc4-ad37-c405d0b55118"
collection: portfolio
---




**Ramjet Optimization Tool**
For this project a first order design tool was developed for the optimization of design parameters for a ram/scramjet engine using MATLAB. To achieve this a first order model of a ram/scramjet was coded. Then using (1) a full factorial design exploration, (2) an SQP optimization, and (3) an fsolve optimization, the design space could be explored, and an optimal multivariate solution or solutions could be easily determined given a desired mission profile.
For a full discussion of this project see https://github.com/eweissm/RamjetOptimizationTool.

**Neural Network Optimized Rocket Controller**
This project involved training a neural network to control a 3 DOF (2 translational and 1 rotational) rocket coming in for a landing. The network needed to land the rocket (have a speed equal to zero at the landing pad) before the fuel ran out. The model was trained by generating a rocket at a random coordinate with a random velocity at t=0s and weighing the performance of the controller to land the rocket. Two different algorithms were investigated (AdaMax and LBFGS), with the AdaMax converging slower but with fewer residuals. It is important to note that the rockets could be spawned in unrecoverable initial conditions, so the residuals never reached zero.
For a full discussion of this project see https://github.com/eweissm/Rocket-Neural-Network-Optimized-Control.

**CFD Mixing Chamber Simulation**
	In this project I used MATLAB to code an incompressible computational fluid dynamics model of a chemical mixing chamber. The simulation employed numerous numerical methods including a central Adams-Bashforth and a WENO-5 TVD-RK4 scheme to solve the convective partial differential terms, while a central Crank-Nicolson with ADI was used for the viscous terms. Next, a V-cycle multigrid with the Gauss-Seidel method was used to solve the poisons equation for the fractional step-method, used to enforce the continuity equation. Finally, in the project a GCI analysis was performed to perform numerical verification.
For a full discussion of this project see: https://github.com/eweissm/MixingChamber_CFD
![image](https://github.com/user-attachments/assets/7440a112-af20-4720-990a-91b7f633f719)

**Generalized Serial Robot Motion Kinetics and Kinematics Solver**
In this project I programmed a user-friendly app which would take user inputs and generate the kinematics and kinetic for a serial robotic arm. The user could then provide desired trajectories and the software would determine joint torques using a closed loop controller.
For a full discussion of this project see: https://github.com/eweissm/SerialRoboticsKinematicsGenerator
![image](https://github.com/user-attachments/assets/e2ebc31a-ded2-40de-8346-005546870301)
