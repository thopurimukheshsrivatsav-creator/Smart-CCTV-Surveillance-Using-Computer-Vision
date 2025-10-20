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

## 🧠 Implementation (Command Prompt)

### ▶️ To Run the First GUI Interface
- Run the following command:
  ```bash
  python main.py


## Launches the Smart CCTV Dashboard with multiple surveillance features.

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
