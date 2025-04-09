# Human Following Luggage Carrying Robot

This project presents the design and implementation of a semi-autonomous luggage-carrying robot that follows a human using Bluetooth RSSI (Received Signal Strength Indicator) and embedded control systems. It integrates various sensors and controllers to provide real-time path following, obstacle avoidance, and directional tracking.

## 📌 Project Objectives

- Assist travelers in carrying heavy luggage autonomously.
- Enable the robot to follow a human using Bluetooth and RSSI-based localization.
- Detect and avoid obstacles in real-time.
- Power the system using batteries and supplementary solar charging.

## 🤖 System Components

- **Microcontroller:** ESP-32
- **Sensors:** 
  - Ultrasonic (for obstacle detection)
  - HMC5883L Magnetometer (for directional sensing)
- **Communication:** Bluetooth (HC-05) using RSSI for proximity tracking
- **Motors:** 300 RPM DC Motors with L298N Motor Driver
- **Power Supply:** 12V 2.6Ah Li-ion battery and 12V 100mA solar panel
- **Interface:** Android app for mobile control and location sharing

## 🔄 Working Principle

- The robot receives Bluetooth signals from the user’s mobile device and calculates the azimuth angle and distance using RSSI.
- It uses motor control logic to follow the user while adjusting its direction based on magnetometer feedback.
- Ultrasonic sensors ensure obstacle avoidance by halting or redirecting the robot.
- A buzzer alerts the user when obstacles are detected.

## 📄 Features

- Autonomous following using wireless localization
- Real-time obstacle detection and buzzer alert
- Directional feedback via compass sensor
- Solar-powered auxiliary energy system
- Controlled via mobile application interface

## 📂 Contents

- `Paper10923.pdf` – Published paper with detailed technical insights

## 🔗 Publication

Published in: *International Journal of Advanced Research in Science, Communication and Technology (IJARSCT)*  
📅 May 2023  
📖 [Read the Paper](https://ijarsct.co.in/Paper10923.pdf)  
📄 DOI: [10.48175/IJARSCT-10923](https://doi.org/10.48175/IJARSCT-10923)
