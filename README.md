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
Implementation (command prompt)-
-python main.py  is used to run the first GUI Interface.
-Launch main.py to open the GUI dashboard.

-Select a feature button (Monitor, Identify, Noise, In-Out, or Record).
1.Face Identification:  Add a new member using the “Add Member” option.
                      Train and test the LBPH model for face recognition.

2.Monitor Feature:   Compares two frames using SSIM to detect stolen objects.

3.Noise Detection:   Calculates absolute frame differences to identify motion.

4.In-Out Detection:  Detects direction of movement (entry or exit).

5.Recording:         Records and saves video feeds locally with timestamps.


-python original.py is used to run the second GUI for sending email alerts.

1.Fire & Smoke Detection: Detects fire or smoke and sends an email alert with the captured image.

2.Prohibited Mode:        Detects anyone entering a no-entry zone and emails an alert with their image.

3.Restricted Mode:        Works for areas allowed only during specific times (like shops); sends alerts if unauthorized people enter.

4.Motion Detection:       Monitors focused areas (like museums) and triggers an alarm if motion is detected.

5.Car Accident Detection: Detects vehicle crashes and sends an emergency email with the crash image and camera location.

6.Face Recognition:       Identifies known people and restricts access to unknown individuals.

7.Weapon Detection:       Detects weapons and sends an email alert with the captured image.

8.Report Generation:      Creates a summary report of all detected events with timestamps and user details.





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


<p align="center">
  <a href="https://github.com/Pawandeep-prog/smart-cctv-ver2.0">
    <img src="https://img.shields.io/badge/Open%20in%20GitHub-Click%20Here-success?style=for-the-badge&logo=github" alt="Open Smart CCTV Repo">
  </a>
</p>



