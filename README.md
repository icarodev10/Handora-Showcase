# 🖐️ Handora - Contactless Industrial Interface System

> A computer vision-based interface designed for industrial environments where touch interaction is restricted or unsafe.

![Status](https://img.shields.io/badge/Status-Closed%20Source-red?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Computer%20Vision-orange?style=for-the-badge)
![Flask](https://img.shields.io/badge/Backend-Flask%20%2F%20FastAPI-green?style=for-the-badge)
![Industry 4.0](https://img.shields.io/badge/Industry%204.0-Smart%20Factory-orange?style=for-the-badge)
![Automation](https://img.shields.io/badge/Category-Industrial%20Automation-blueviolet?style=for-the-badge)

## 🎥 Project Demo

https://github.com/user-attachments/assets/91cd9e1b-5e02-4a31-9dd4-df54624c8ec5

---

## 💡 About The Project

**Handora** solves a critical problem in Industry 4.0: how to interact with digital systems when your hands are dirty, greasy, or when working in sterile environments.

Using **MediaPipe** for hand tracking, it allows operators to control data dashboards, request parts from the warehouse, and navigate the OS using purely **contactless gestures**, integrated directly with the **SGMI** (Industrial Maintenance Management System).

### 🚀 Key Features

* **👆 Touchless Navigation:** Mouse cursor simulation using 3D Euclidean distance with Hysteresis algorithms to prevent cursor jitter.
* **🏭 Industrial Integration:** Real-time connection to the SGMI database to display asset status and sensor data.
* **🔐 Role-Based Access Control:** Secure authentication flow (Admin/Operator) using hashed credentials.
* **🛡️ Safety First:** Designed to avoid false positives in busy industrial backgrounds.

---

## 🛠️ Tech Stack & Architecture

Although the source code is proprietary, the system was built using a robust modern stack:

* **Core Backend:** Python 3.11 (Optimized for MediaPipe compatibility).
* **API Layer:** Flask & FastAPI (Handling asynchronous requests and WebSockets).
* **Computer Vision:** OpenCV + MediaPipe (Low-latency tracking).
* **Database:** MySQL (Relational Data for Auth & Industrial Logs).
* **Communication:** REST API & WebSockets for real-time dashboard updates.

### System Architecture
The project follows a **Dual-Service Architecture**:
1.  **Handora Core:** A dedicated service for processing camera feed, detecting landmarks, and translating gestures into OS commands.
2.  **SGMI Backend:** A web service managing the logic, database connections, and frontend dashboards.

---

## 🔒 Access & License

This project was developed as a **Project for Industrial Automation**.
The source code is currently **Closed Source** as it belongs to the development team and the institution.

This repository serves as a technical portfolio and documentation of the technology used.

---

## 👥 Development Team

This project was a collaborative effort developed at SENAI by:

* **Icaro de Souza de Lima** - [GitHub](https://github.com/icarodev10)
* **Luís Miguel da Costa** - [GitHub](https://github.com/LuisCosta321)
* **Marcos Vinícius Cavalaro** - [GitHub](https://github.com/MarcosCavalaro)
* **Kaique Borlenghi da Silva** - [GitHub](https://github.com/KaiqueBorlenghi)
* **Nicolas Eduardo de Godoy** - [GitHub](https://github.com/NicolasEGodoy)

---

### 📞 Contact
Interested in the technology or implementation details? Feel free to reach out via LinkedIn!
