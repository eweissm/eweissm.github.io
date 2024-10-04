---
title: "Automatic Zen Garden"
excerpt: "Automatic Zen Garden ![Untitled video - Made with Clipchamp](https://github.com/eweissm/Autonomous-Zen-Garden/assets/73143081/3ab6f555-8f9d-4b08-80e6-b3ee96074b49)"
collection: portfolio
---

Shown below is an automatic Zen Garden, which uses a 2 DOF SCARA robot arm to position a ball bearing moving through the sand. This project consisted of numerous elements, including:
* The design of a continuous rotation SCARA arm and its integration into the wooden housing
  *	This involved a vibration analysis to prevent the stepper motor from exciting an unlucky natural frequency of the box, causing an obnoxious noise.
*	A hall effect homing sensor
*	Low Level Controller (Arduino)
  *	Homing sequence which would occur on system power up.
  *	Two-way serial communication with the controlling computer.
  *	PD controller for position control
*	High Level Controller (Python)
  *	Used a root finding algorithm to find the optimal path and joint angles for the robotic arm. 
  *	Custom GUI, which would take user input and use serial communication to talk with an Arduino to control the joint angles. Shown below is the UI, which outlines the workspace of the robot (black dotted line) and the selected preset path the arm can follow when the “follow path” button is pressed (blue dotted line). The user can scroll through various presets by selecting the “Change Path” button. Finally, if the user inputs custom X and Y coordinates, once the “Update Coordinates” button is pressed, the arm will move to that location, and the arm joint angles and position will be shown. 
  *	The preset paths can be passed through a parametric equation or through a G-code file via a custom regex interpreter I wrote for basic G-code commands.

See https://github.com/eweissm/Autonomous-Zen-Garden for code (note the code will not run unless an Arduino is plugged into the computer or if all lines beginning with “ser” are commented out).


https://github.com/user-attachments/assets/87ad1c28-59f6-4abb-af95-3c5c3388c9fe

![image](https://github.com/user-attachments/assets/0cb128d9-cbb4-4c88-910d-e1362cb3b47e)

![image](https://github.com/user-attachments/assets/915888d6-324d-4819-9a0b-257dcbc093f1)

![image](https://github.com/user-attachments/assets/642310da-0459-4fdb-82ea-550516700b7d)

![image](https://github.com/user-attachments/assets/641643cf-6f32-4fd3-b6bc-c3577a73c673)

![image](https://github.com/user-attachments/assets/fc0f7de1-8f93-44bb-ab4b-4f39f6c8822f)

![image](https://github.com/user-attachments/assets/37994141-4010-423b-8d04-ce67b0d2fade)

![image](https://github.com/user-attachments/assets/e81f3b05-42f6-422d-98ed-dbd8f6811b9c)
