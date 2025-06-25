# Vision-Based Robotic Arm Control

A Python-based robotic system that uses computer vision to detect ArUco markers and perform autonomous pick-and-place tasks with a robotic arm.

## 🧠 Overview
This project integrates real-time ArUco marker detection with inverse kinematics and serial communication to control a robotic arm. It demonstrates a low-cost vision-guided automation system capable of spatial recognition and physical manipulation.

## 🔧 Features
- Detects workspace and target objects using ArUco markers via OpenCV
- Converts camera coordinates into joint angles using inverse kinematics
- Controls a robotic arm using serial communication with Arduino
- Includes mechanical compensations for backlash and camera alignment
- Supports manual override through keyboard input for testing/demo

## 🛠 Technologies Used
- Python  
- OpenCV (ArUco module)  
- Arduino (Serial communication)  
- Inverse Kinematics & Coordinate Transformation  
- Real-time video processing  

## 🎥 Demo
Video which shows the results of the code:
https://www.youtube.com/watch?v=SUgCcF-lWCI&ab_channel=NatanNaert



## 🚀 How to Run
1. Upload the arduino code on the arduino board.
2. Unplug the Arduino board and close the arduino IDE.
3. Place both Python files in the same folder.
4. Adapt the COM port in the 'braccio_control_python.py' file to match the COM port of your arduino.
5. Install the required packages.
6. Run 'Aruco_detection_V2' to run the robot arm with the 4 Aruco Markers. (sse video)
7. Use the different definitions to control the arm.

## ⚠️ Note
Hardware testing was done under limited conditions using partially functional robotic arms. The system is fully functional in simulation and under standard conditions.

---

**Project by Mudit Rungta and team — under IE410: Introduction to Robotics.**
