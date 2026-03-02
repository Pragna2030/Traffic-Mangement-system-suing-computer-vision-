🚦 AI-Based Traffic Management System

An intelligent Traffic Management System that dynamically controls traffic signal timing using Computer Vision and Deep Learning. Instead of fixed timers, this system adjusts green signal duration based on real-time vehicle density to reduce congestion and improve traffic flow.

📌 Problem Statement

Traditional traffic signals operate on fixed time intervals, regardless of vehicle density on each lane. This leads to:

Increased waiting time

Traffic congestion

Fuel wastage

Higher pollution levels

This project aims to solve this issue using real-time vehicle detection and dynamic signal control.

🎯 Project Objective

To develop an AI-based system that:

Detects and counts vehicles from traffic video

Calculates traffic density per lane

Dynamically adjusts signal timing

Reduces congestion and improves efficiency

🛠️ Technologies Used
🔹 Backend

Python

OpenCV – Video frame processing

Ultralytics YOLO – Real-time vehicle detection

Flask – Backend API development

Pyngrok – Exposing local server for testing

collections (defaultdict) – Vehicle counting

os – File handling

🔹 Frontend

Streamlit – Interactive web interface

requests – Frontend-backend communication

MoviePy – Video processing

time – Timing operations

⚙️ How It Works

User uploads traffic video via Streamlit interface.

Video is sent to Flask backend.

OpenCV processes video frame-by-frame.

YOLO model detects vehicles (cars, bikes, buses, trucks).

Vehicle count is calculated for each lane.

Signal timing is dynamically adjusted based on traffic density.

Processed video with detections is displayed to the user.

📊 Features

Real-time vehicle detection

Dynamic signal timing logic

User-friendly interface

End-to-end integration (Frontend + Backend)

Smart city application potential

🚧 Challenges Faced

Handling low-light and shadow conditions

Maintaining real-time processing speed

Detecting overlapping vehicles

Reducing false detections

📈 Outcome

The system successfully demonstrates dynamic traffic signal control based on real-time vehicle density. Compared to fixed-timer systems, it improves traffic flow efficiency and reduces congestion in simulated scenarios.

📚 Learning Outcomes

Practical implementation of Computer Vision

Real-time object detection using YOLO

Backend API development with Flask

Frontend-backend integration

Performance optimization for real-time systems
