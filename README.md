# 🕷️ Hexapod v1 | Robotics Club IIT Delhi

The **Hexapod v1** is an advanced 6-legged walking robot featuring 18 Degrees of Freedom (3-DOF per leg).This iteration focuses on high-torque serial bus actuation and a streamlined ESP32-based control architecture.

---

## 🏗️ Hardware Architecture

### 1. Actuators: Waveshare SC15 Serial Bus Servos
Unlike standard PWM servos, the SC15 motors provide:
* **Daisy-Chained Wiring:** Only one data line is needed per leg (or even the whole body), drastically reducing cable clutter.
* **Two-way Feedback:** Real-time monitoring of position, speed, torque, voltage, and temperature.
* **Precision:** 17kg.cm stall torque with 0.16° position resolution.

### 2. Controller: Waveshare ESP32 Servo Driver Board
* **Module:** ESP32-WROOM-32.
* **Features:** Integrated serial bus servo interface, Wi-Fi/Bluetooth connectivity for remote operation, and an onboard OLED header for status debugging.

### 3. Power System
* **Custom Power PCB:** A bespoke power distribution board designed to channel high current to 24 servos, preventing voltage drops during high-torque maneuvers.


---


---


## 👥 Team & Mentorship

### 🎓 Mentors
The project is developed under the expert guidance of our faculty mentors at IIT Delhi:

| Name | Designation | Role |
| :--- | :--- | :--- |
| **Raj Gowtham** | Btech 2nd Year | Lead Advisor, MECHANICAL|
| **Shivanshu aryan** | Btech 2nd Year| Lead Advisor, SIMULATION |

---

### 🛠️ Core Project Team
A multidisciplinary team of students from the **Robotics Club, IIT Delhi** is responsible for the design, simulation, and fabrication of the Hexapod.

| Name | Role | Core Responsibility |
| :--- | :--- | :--- |
| **Nikhil** | **Mechanical** | CAD Design, URDF Export |
| **Vijay** | **Mechanical** | CAD Design, URDF Export |
| **Gyan** | **Mechanical and PCB** | CAD Design, Power PCB design |
| **Vanshika** | **Mechanical and PCB** | CAD Design, Power PCB design |
| **Uday** | **Simulation** | PyBullet Environment & Gait Cycle |
| **Harshita** | **Simulation** | PyBullet Environment & Gait Cycle |
| **Kartikey** | **Simulation** | PyBullet Environment & Gait Cycle |
| **Pranav** | **Simulation** | PyBullet Environment & Gait Cycle |
| **Akshara** | **Simulation** | PyBullet Environment & Gait Cycle|
---
