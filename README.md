# Line Follower Robot using Arduino

This project is about building a **Line Follower Robot** using **Arduino UNO**. The robot follows a pre-defined black line on a white surface (or vice versa) using IR sensors to detect the path and adjust its movement.

---

## 🚀 Features
- Automatically follows a line using IR sensors.
- Real-time path correction using motor control.
- Smooth turns and adjustments.
- Compact and efficient design.

---

## 🖼️ Project Overview
### Robot Design:
![Line Follower Robot](./img/Arduino-Line-Follower-Robot-Image-10-760x440.jpg)
![Line Follower Robot in Action](./img/Arduino-Line-Follower-Robot-Image-9-760x440.jpg)

### Circuit Diagram:
![Circuit Diagram](./img/Line-Follower-Circuit-Diagram.png)

---

## 🛠️ Components Used
- Arduino UNO
- L298N Motor Driver Module
- IR Sensor Modules (x2)
- DC Motors (x2)
- Robot Chassis with Wheels
- Jumper Wires
- 9V Battery with Battery Holder

---

## 📁 Code Structure
```plaintext
├── controller.ino   # Code to handle sensor data and motor control
├── moter.ino        # Code to define motor operations
├── images/          # Project images and circuit diagram
└── README.md        # Project documentation
