# Driver-Drowsiness-Project
🚗 Driver Drowsiness Detection System
A real-time Driver Drowsiness Detection System that uses computer vision to monitor a driver’s eye activity and alert the driver when signs of drowsiness are detected.
This project helps in preventing road accidents caused by fatigue and lack of attention.

📌 Project Overview
Driver fatigue is one of the major causes of road accidents.
This project detects whether a driver is drowsy or active by continuously monitoring eye movements through a webcam.

When the driver’s eyes remain closed for a certain period of time, an alarm is triggered to warn the driver.

🎯 Objectives
Detect the driver's face and eyes in real time

Identify eye closure using facial landmarks

Calculate Eye Aspect Ratio (EAR)

Trigger an alert when drowsiness is detected

Provide a simple and fast real-time solution

🛠️ Technologies Used
Python

OpenCV

Dlib

NumPy

Imutils

⚙️ System Requirements
Python 3.7 or above

Webcam

Windows / Linux OS

📂 Project Structure
driver-drowsiness-detection/
│
├── shape_predictor_68_face_landmarks.dat
├── drowsiness_detection.py
├── alarm.wav
└── README.md
🔍 Working Principle
Capture video frames from the webcam.

Detect the face using a face detector.

Detect facial landmarks for the eyes.

Calculate the Eye Aspect Ratio (EAR).

If EAR falls below a threshold for a continuous number of frames:

The driver is considered drowsy

An alarm sound is generated

🧠 Eye Aspect Ratio (EAR)
EAR is used to measure eye openness.

If the eye remains closed for a defined time, the system detects drowsiness.

▶️ How to Run the Project
Step 1 – Install required libraries
pip install opencv-python dlib imutils numpy
Step 2 – Download landmark model
Download the file:

shape_predictor_68_face_landmarks.dat
and place it inside the project folder.

Step 3 – Run the program
python drowsiness_detection.py
🚨 Output
The system shows live camera feed

Displays eye landmarks

Plays an alarm sound when drowsiness is detected

✅ Features
Real-time detection

Lightweight and fast

Easy to use

Works with a standard webcam

⚠️ Limitations
Performance may reduce in low light conditions

Works best when the face is clearly visible

Not suitable when the driver wears dark sunglasses

🚀 Future Enhancements
Mobile application integration

Yawn detection support

Head pose estimation

Deep learning based detection model

📄 Conclusion
This Driver Drowsiness Detection System provides a simple and effective solution to detect fatigue in drivers and helps reduce accident risks by issuing timely alerts.
It can be further enhanced using deep learning and advanced driver monitoring techniques.
