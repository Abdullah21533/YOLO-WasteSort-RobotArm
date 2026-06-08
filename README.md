# YOLO-WasteSort-RobotArm

## ♻️ Overview

YOLO-WasteSort-RobotArm is an intelligent autonomous waste sorting system developed using Raspberry Pi 5, Computer Vision, and Robotics. The project combines real-time YOLO object detection, AprilTag-based localization, closed-loop motor feedback control, and a 5-DOF robotic manipulator to automatically identify, pick, and sort waste objects into designated recycling bins.

The system is designed as a low-cost and scalable solution for smart recycling, industrial automation, and educational robotics applications.

---

## 🚀 Key Features

* Real-time YOLO-based waste object detection
* Autonomous pick-and-place operation
* AprilTag-assisted localization and coordinate mapping
* Raspberry Pi 5 embedded control platform
* ADS1115 16-bit feedback acquisition system
* Closed-loop position control using potentiometer feedback
* Multi-bin intelligent waste segregation
* Custom 5-DOF robotic manipulator
* Differential gripper mechanism
* Real-time object classification and sorting

---

## 🏗 System Architecture

Object Detection (YOLO)

↓

Object Classification

↓

AprilTag Localization

↓

Coordinate Mapping

↓

Motion Planning

↓

Robotic Arm Control

↓

Object Grasping

↓

Waste Bin Sorting

---

## 🛠 Hardware Components

| Component            | Description                        |
| -------------------- | ---------------------------------- |
| Raspberry Pi 5       | Main processing unit               |
| USB Camera           | Real-time image acquisition        |
| ADS1115              | 16-bit Analog-to-Digital Converter |
| L298N Motor Drivers  | DC Motor Control                   |
| Potentiometers       | Joint Feedback Sensors             |
| 5-DOF Robotic Arm    | Manipulation System                |
| Differential Gripper | Object Grasping Mechanism          |
| Buck Converter       | Power Regulation                   |
| 12V Power Supply     | System Power Source                |

---

## 💻 Software Stack

* Python
* OpenCV
* Ultralytics YOLO
* AprilTag Detection
* NumPy
* SciPy
* Raspberry Pi GPIO
* Multithreading

---

## 📂 Repository Structure

```text
YOLO-WasteSort-RobotArm
│
├── README.md
├── LICENSE
├── Roboric_arm_code.py
├── BOM.pdf
├── Schematic Diagram.png
├── Cover Photo 01.jpeg
├── Cover Photo 02.jpeg
├── Cover Photo 03.jpeg
├── Cover Photo 04.jpeg
├── Cover Photo 05.jpeg
├── robo video.mp4
└── pdfcoffee.com_feedback-35-001-usb-mentor-pdf-free.pdf
```

---

## 📸 Project Demonstration

The robotic system successfully:

* Detects recyclable waste using YOLO.
* Calculates object position relative to an AprilTag reference frame.
* Converts image coordinates into robot coordinates.
* Moves the robotic arm autonomously.
* Grasps the target object.
* Places the object into the correct recycling bin.

The repository includes demonstration images, videos, hardware schematics, and implementation source code.

---

## 🎯 Applications

* Smart Recycling Systems
* Industrial Waste Management
* AI-Powered Automation
* Educational Robotics
* Embedded AI Systems
* Computer Vision Research
* Intelligent Material Sorting

---

## 🔬 Future Work

* Integration of YOLOv11 and lightweight transformer models
* Mobile robot navigation and autonomous bin positioning
* Cloud-based monitoring dashboard
* Multi-camera object tracking
* Reinforcement learning for adaptive grasping
* Edge-AI optimization for industrial deployment

---

## 👨‍💻 Author

### Muhammad Abdullah

BS Software Engineering
The Islamia University of Bahawalpur (IUB), Pakistan

Research Interests:

* Computer Vision
* Robotics
* Lightweight Deep Learning
* Embedded AI
* Medical Imaging AI
* Edge Intelligence

---

## 👨‍🏫 Research Mentor

### Dr. Engr. Dileep Kumar

Faculty of Engineering
Department of Electronic Engineering
The Islamia University of Bahawalpur (IUB)

---

## 📜 License

This project is released under the MIT License.

---

## ⭐ Citation

If you find this project useful in your research, please consider starring the repository and citing the project appropriately.

© 2026 Muhammad Abdullah. All Rights Reserved.
