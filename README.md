# Gesture Control Car

A wireless robotic car controlled entirely by hand gestures using embedded systems and motion sensing.

##  Overview

This project uses a glove equipped with an MPU6050 sensor to detect hand movement and orientation. The motion data is processed using an Arduino Nano and transmitted wirelessly via NRF24L01 modules to an Arduino Uno mounted on the car, which controls the car’s movement in real time.

Instead of traditional control methods like mobile apps or line-following sensors, the car responds directly to the user's hand gestures.

---

##  Components Used

* Arduino Uno
* Arduino Nano
* MPU6050 Gyroscope & Accelerometer
* NRF24L01 Wireless Module
* L298N Motor Driver
* DC Motors & Chassis
* Battery Pack

---

##  System Workflow

1. The MPU6050 detects hand tilt and motion.
2. Arduino Nano reads and processes the sensor values.
3. NRF24L01 sends the data wirelessly.
4. Arduino Uno receives the data on the car side.
5. Motor directions are controlled based on the received gesture values.

---

##  Features

* Real-time gesture control
* Wireless communication
* Smooth directional movement
* Embedded systems & sensor integration
* Simple and intuitive control mechanism

---

##  Technologies

* Embedded Systems
* Arduino Programming
* Wireless Communication
* Signal Processing Basics
* Motion Sensing

---

##  Project Demo

(Add your project photos/videos here)

---

##  GitHub Repository


