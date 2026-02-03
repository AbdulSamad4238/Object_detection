🚀 Real-Time Object Detection & Tracking using YOLOv8

📌 Overview

This project implements a real-time object detection and tracking system using YOLOv8 and OpenCV. It detects and tracks multiple objects such as persons, bicycles, and cars from a video stream using a pre-trained deep learning model.

🧠 Tech Stack

Language: Python

Framework: Ultralytics YOLOv8

Libraries: OpenCV, NumPy

Domain: Computer Vision, Deep Learning

Model: YOLOv8 Nano (yolov8n.pt)

✨ Features

Real-time object detection

Multi-object tracking with persistent IDs

Efficient YOLOv8 Nano model for fast inference

Video-based detection pipeline

Clean and scalable project structure

📂 Project Structure
object-detection-yolov8/
│
├── main.py
├── person-bicycle-car-detection.mp4
├── yolov8n.pt
├── requirements.txt
└── README.md

▶️ Usage

Run the application using:

python main.py


Press q to exit the video window.

🔄 Workflow

Load YOLOv8 pre-trained model

Read video frames using OpenCV

Perform object detection and tracking

Draw bounding boxes and labels

Display real-time output

📊 Use Cases

Traffic and vehicle monitoring

Surveillance and security systems

Smart city applications

Autonomous systems preprocessing

Computer vision learning projects

🚀 Future Enhancements

Webcam and live stream support

Object counting and analytics

Save output video

GPU acceleration (CUDA)

Custom dataset training
