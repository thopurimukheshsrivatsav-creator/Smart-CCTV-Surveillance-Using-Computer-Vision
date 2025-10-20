# 🎥 Smart CCTV  
### Group 4  
👩‍💻 1. Deekshitha Sarabudla  
👨‍💻 2. Thopuri Mukhesh Srivatsav  
👨‍💻 3. Shashank Reddy Peta  

---

## 📘 Overview  
**Smart CCTV** is a Python-based GUI application that transforms a normal camera into a **smart surveillance system**.  
Built using **Computer Vision** and **Machine Learning**, it enhances traditional CCTV systems by detecting thefts, identifying faces, monitoring motion, detecting fire, and sending real-time alerts via email.

This project includes **two main GUI systems**:  
1. **Main GUI (main.py)** – Handles object monitoring, face recognition, motion detection, and video recording.  
2. **Alert GUI (original.py)** – Detects emergency situations such as fire, accidents, and restricted area violations, and sends alerts through email.

It supports **Windows**, **Linux**, and **macOS** platforms.

---

## ⚙️ Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python 3 |
| **Libraries / Frameworks** | OpenCV, NumPy, scikit-image, Tkinter, smtplib, imutils, DNN Module, Pillow |
| **Algorithms** | Haar Cascade (Face Detection), LBPH (Face Recognition), SSIM (Object Comparison) |

---

## 📦 Required Packages

Install the following dependencies before running the project:

```bash
pip install opencv-contrib-python
pip install numpy
pip install pillow
pip install imutils
pip install pandas
pip install matplotlib
pip install tk
pip install playsound==1.2.2
pip install smtplib

# 🧠 Implementation Guide

This section explains how to run and use both **GUI interfaces** of the Smart CCTV project via the **Command Prompt**.

---

## 🎛️ Running the First GUI — Smart CCTV Dashboard

To launch the main interface, run:
```bash
python main.py
🖥️ Overview
This GUI opens the Smart CCTV Dashboard where you can monitor different smart surveillance features.

🧩 Features
1. 👤 Face Identification
Add a new member using the “Add Member” option.

Train and test the LBPH (Local Binary Pattern Histogram) model for face recognition.

2. 🧳 Monitor Feature
Uses SSIM (Structural Similarity Index) to compare frames and detect stolen or missing objects.

3. 🔊 Noise Detection
Calculates absolute frame differences to identify motion or unusual activity.

4. 🚪 In–Out Detection
Detects the direction of movement — whether a person is entering or exiting.

5. 🎥 Recording
Records and saves video feeds locally with automatic timestamps.

🚨 Running the Second GUI — Email Alert & Emergency System
To launch the alert system interface, run:

bash
Copy code
python original.py
🔥 Emergency Features
1. 🔥 Fire & Smoke Detection
Detects fire or smoke in the frame and sends an email alert with the captured image.

2. 🚫 Prohibited Mode
Identifies people entering no-entry zones and emails their images as alerts.

3. ⏰ Restricted Mode
Monitors time-based access zones (e.g., after shop hours) and sends alerts for unauthorized entries.

4. 🎯 Motion Detection
Detects motion in focused or high-security areas (like museums) and triggers an alarm.

5. 🚗 Car Accident Detection
Identifies vehicle accidents and emails emergency alerts with crash images and location.

6. 🧍 Face Recognition
Recognizes registered individuals and restricts access to unregistered or unknown people.

7. 🔫 Weapon Detection
Detects weapons and immediately sends an alert email with the image evidence.

8. 🧾 Report Generation
Generates a summary report of all detected events with timestamps and user details.

🌐 Source Code
📎 Original Repository: Smart CCTV on GitHub
