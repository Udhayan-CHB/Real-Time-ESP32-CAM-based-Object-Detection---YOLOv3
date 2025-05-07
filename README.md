# Real-Time-ESP32-CAM-based-Object-Detection-YOLOv3

# Overview

This project demonstrates real-time object detection using an ESP32-CAM module for video streaming and a YOLOv3 deep learning model for detecting objects. The ESP32-CAM sends video frames over Wi-Fi to a Python script running on a PC, which performs detection using OpenCV and YOLOv3.

> Ideal for smart surveillance, robotics, IoT-based monitoring systems, or edge-AI prototypes.

---

# Features

- Real-time MJPEG video streaming from ESP32-CAM over Wi-Fi
- Object detection with YOLOv3 (pre-trained COCO model)
- Live video feed with bounding boxes and class labels
- Lightweight, runs smoothly on standard laptops
- Easy integration with other IoT systems

---

# Hardware Requirements

- ESP32-CAM module (AI-Thinker or similar)
- USB to TTL Serial Converter
- Jumper wires
- Host PC with Wi-Fi (for receiving stream)
- Optional: Breadboard, battery pack

---

# Software Requirements

# ESP32 Side:
- Arduino IDE or PlatformIO
- ESP32 Board Support Package
- Libraries:
  - ESP32 WebServer
  - WiFi.h
  - esp_camera.h

# Host (PC) Side:
- Python 3.8 or higher
- OpenCV (cv2)
- NumPy
- YOLOv3 weights & config files
- Webcam or IP stream support

Install dependencies using:

`bash
pip install opencv-python numpy cvlibs


