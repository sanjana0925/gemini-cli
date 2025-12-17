# Real-Time Object Detection using YOLO and OpenCV

## 1. Overview
This repository contains a simple object detection project that identifies and localizes multiple objects in images and videos using a YOLO model with Python and OpenCV.  
The system draws bounding boxes around detected objects and shows their class labels and confidence scores.

## 2. Features
- Detects common objects (such as person, car, bicycle, dog, etc.) in images and video streams.  
- Supports three input modes: image file, video file, and webcam.  
- Simple code structure, suitable for mini‑project or college submissions.

## 3. How It Works
The processing pipeline of the project is:

**Input (image / video / webcam) → Preprocessing (resize, normalize) → YOLO object detection model → Post‑processing (NMS, confidence threshold) → Output frame with bounding boxes and labels.**

A pretrained YOLO model trained on a standard dataset (such as COCO) is used for detection.

## 4. Technologies Used
- Language: Python 3  
- Libraries:
  - OpenCV  
  - NumPy  
  - YOLO implementation (for example, via OpenCV DNN or a ready library like Ultralytics)  
- Platform: Works on Windows, Linux, or macOS (with Python installed)

## 5. Repository Structure
update README for object detection project
