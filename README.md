# Smart-CCTV-Surveillance-Using-Computer-Vision

             smart-cctv
                                          Group 4
                                1. Deekshitha Sarabudla
                                2. Thopuri Mukhesh Srivatsav
                                3. Shashank Reddy Peta
 
This is a gui interface for converting your normal camera to smart camera. Smart CCTV is a Python-based GUI application built using Computer Vision. It enhances traditional CCTV by adding intelligent detection capabilities.

The first GUI system can detect theft, identify faces, monitor noise/motion, track visitors, and record video automatically. We can run it by typing  command  - python main.py in command prompt.

The second system is capable of detecting emergency situations like fire detection, prohibited mode, restricted mode, accident detection, face detection  and sending an alert email to the given email address. We can implement this interface using  typing - python original.py in the prompt.

It works on Windows, Linux, and macOS platforms.

Technologies Used:

Programming Language:        Python 3
Libraries / Frameworks:      OpenCV, NumPy, scikit-image ,Tkinter ,smtplib, imutils, OpenCV and DNN Module.

Algorithms Used: Haar Cascade for face detection.
                 LBPH (Local Binary Pattern Histogram) for face recognition.
                 SSIM (Structural Similarity Index) for object comparison.

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



Source link - https://github.com/Pawandeep-prog/smart-cctv-ver2.0
