Project Description:
This project aims to control four servo motors to simulate basic movement patterns for a humanoid robot, incorporating a walking algorithm to simulate bipedal locomotion.

Main Features:
	•	Precise control of four servos working in unison
	•	Ability to hold each servo’s position at a 90° angle
	•	Walking pattern algorithm designed for two-legged motion

Required Hardware:
	•	Arduino Uno or Nano board
	•	4 servo motors
	•	Jumper wires
	•	5V external power supply

Steps to Install:
	1.	Attach the servo motors to pins 3, 5, 6, and 10 on the Arduino board.
	2.	Upload the walking control code onto the Arduino.
	3.	Connect the power supply to the system.

Walking Algorithm:
The walking action is broken down into two phases:
	1.	Right Leg Movement:
	•	Lift the right leg (rotate the hip by 20°)
	•	Swing the leg forward (rotate the knee by 20°)
	•	Lower the leg to the ground
	•	Shift the body weight slightly to the left (-10° adjustment)
	2.	Left Leg Movement:
	•	Lift the left leg
	•	Swing the leg forward
	•	Lower the leg back to the ground
	•	Shift the body weight slightly to the righ
