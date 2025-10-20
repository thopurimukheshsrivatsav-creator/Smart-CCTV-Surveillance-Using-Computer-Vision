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
🚀 Implementation Steps
🖥️ 1. First GUI – Smart CCTV Dashboard
To launch the main GUI:

bash
Copy code
python main.py
Features:
Face Identification:

Add a new member using “Add Member”.

Train and test the LBPH model for face recognition.

Monitor Feature:

Compares frames using SSIM to detect stolen or missing objects.

Noise Detection:

Detects motion by analyzing frame differences.

In–Out Detection:

Detects movement direction (entry or exit).

Recording:

Records and saves live video with timestamps.

🔥 2. Second GUI – Alert & Emergency System
To launch the second GUI:

bash
Copy code
python original.py
Features:
Fire & Smoke Detection:

Detects fire/smoke and emails an alert with the captured image.

Prohibited Mode:

Detects unauthorized entry in restricted areas and sends an alert.

Restricted Mode:

Alerts when someone enters during unauthorized hours (e.g., shop after closing).

Motion Detection:

Triggers alarm when movement is detected in a focused zone (e.g., museum).

Car Accident Detection:

Detects accidents and emails emergency images with location details.

Face Recognition:

Identifies registered faces and restricts unknown individuals.

Weapon Detection:

Detects weapons and sends an alert with the captured image.

Report Generation:

Generates a detailed summary report of all detected events with timestamps and user info.

📎 Source Code
Original Repository: Smart CCTV - GitHub Link
