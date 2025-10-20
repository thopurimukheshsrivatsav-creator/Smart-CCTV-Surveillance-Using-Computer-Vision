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
🧠 Implementation (Command Prompt)
▶️ To Run the First GUI Interface

Run the following command:

python main.py


Launches the Smart CCTV Dashboard with multiple surveillance features.

Features:

Face Identification

Add a new member using the “Add Member” option.

Train and test the LBPH (Local Binary Pattern Histogram) model for face recognition.

Monitor Feature

Compares two frames using SSIM (Structural Similarity Index) to detect stolen or missing objects.

Noise Detection

Calculates absolute frame differences to identify motion or unusual activity.

In–Out Detection

Detects the direction of movement (entry or exit).

Recording

Records and saves video feeds locally with automatic timestamps.

🚨 To Run the Second GUI (Email Alert System)

Run the following command:

python original.py


Launches the Emergency Detection and Alert System, capable of sending automated email notifications.

Features:

Fire & Smoke Detection

Detects fire or smoke and sends an email alert with the captured image.

Prohibited Mode

Detects entry in restricted/no-entry zones and sends an alert email with the intruder’s image.

Restricted Mode

Monitors time-based restricted areas (e.g., shops after closing hours) and sends alerts if unauthorized access occurs.

Motion Detection

Detects motion in focused areas (e.g., museums, offices) and triggers an alarm.

Car Accident Detection

Detects vehicle crashes and sends an emergency email alert with the captured image and camera location.

Face Recognition

Identifies known individuals and restricts access to unknown persons.

Weapon Detection

Detects weapons and sends an alert email with an image of the event.

Report Generation

Generates a summary report of all detected events with timestamps and user details.
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


🧠 Implementation (Command Prompt)
▶️ To Run the First GUI Interface

Run the following command:

python main.py


Launches the Smart CCTV Dashboard with multiple surveillance features.

Features:

Face Identification

Add a new member using the “Add Member” option.

Train and test the LBPH (Local Binary Pattern Histogram) model for face recognition.

Monitor Feature

Compares two frames using SSIM (Structural Similarity Index) to detect stolen or missing objects.

Noise Detection

Calculates absolute frame differences to identify motion or unusual activity.

In–Out Detection

Detects the direction of movement (entry or exit).

Recording

Records and saves video feeds locally with automatic timestamps.

🚨 To Run the Second GUI (Email Alert System)

Run the following command:

python original.py


Launches the Emergency Detection and Alert System, capable of sending automated email notifications.

Features:

Fire & Smoke Detection

Detects fire or smoke and sends an email alert with the captured image.

Prohibited Mode

Detects entry in restricted/no-entry zones and sends an alert email with the intruder’s image.

Restricted Mode

Monitors time-based restricted areas (e.g., shops after closing hours) and sends alerts if unauthorized access occurs.

Motion Detection

Detects motion in focused areas (e.g., museums, offices) and triggers an alarm.

Car Accident Detection

Detects vehicle crashes and sends an emergency email alert with the captured image and camera location.

Face Recognition

Identifies known individuals and restricts access to unknown persons.

Weapon Detection

Detects weapons and sends an alert email with an image of the event.

Report Generation

Generates a summary report of all detected events with timestamps and user details.
