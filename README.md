# Smart Lab

An IoT-based Smart Laboratory Management System designed to automate laboratory access, attendance tracking, online examinations, and remote lab control.

## 📌 Overview

Smart Lab is an integrated solution that combines IoT hardware and intelligent software to modernize traditional academic laboratories.

The system enhances security through dual-factor authentication using **RFID cards** and **Face Recognition**, automates attendance recording, provides an online examination platform, and allows remote laboratory control.

---

## ✨ Features

### 🔐 Secure Access Control

* RFID Card Authentication
* Real-time Face Recognition
* Automatic Door Lock/Unlock using Servo Motor
* LCD Status Display
* White LED Indicators

### 📝 Attendance Management

* Automatic attendance recording
* Date and time logging
* Student attendance history

### 🖥 Web Platform

#### Doctor Module

* Login System
* Create Exams
* Manage Exams
* View Results
* Control Laboratory Lighting Remotely

#### Student Module

* Login System
* View Available Exams
* Submit Exams
* View Results
* Check Attendance Records

### 🤖 IoT Integration

* ESP32 Communication
* RFID Reader Integration
* Camera Triggering
* Servo Motor Control
* LED and LCD Management

---

## 🏗 System Architecture

The authentication workflow follows these steps:

1. User scans RFID card.
2. Camera captures face image.
3. Face Recognition server verifies identity.
4. Access is granted or denied.
5. Attendance is recorded automatically.
6. Servo motor opens the door.
7. Door locks again after a predefined interval.

---
## 🛠 Images
<img width="1280" height="960" alt="SmartLab 3D Image 1" src="https://github.com/user-attachments/assets/b2f85b3e-2b47-4d2c-b208-f91948d05c1b" />
<img width="1280" height="960" alt="SmartLab 3D Image 2" src="https://github.com/user-attachments/assets/675b3174-89ff-48fe-86a3-cead25af16d7" />


## 🛠 Technologies Used

### Hardware

* ESP32
* MFRC522 RFID Reader
* Camera Module
* Servo Motor
* LCD Display
* LEDs

### Software

* Python
* Face Recognition
* HTML
* CSS
* JavaScript
* MySQL
* Flask *(if used)*
* Arduino IDE


## 👥 Team Members

* Ehab Mustafa Abd El-Monem Al-Rifai
* Muhamed Osama Attia Ahmed Yousef
* Ahmed Muhamed Mohamed Abdo El-Sady
* Emad Mohamed Abd El-Aziz Shabana
* Ibrahim El-Sayed Shaaban Mustafa

---

## 🎓 Graduation Project

Faculty of Computers and Artificial Intelligence
Damietta University
Academic Year 2025–2026

Supervisor:
**Prof. Dr. Ahmed Mohamed Rabea**

---

## 📄 License

This project was developed for academic purposes as a Graduation Project.
