
# Full-Body Landmarks Detection using MediaPipe Holistic

This project implements real-time full-body landmark detection using **MediaPipe Holistic**, a framework designed for detecting and rendering facial, hand, and pose landmarks. The solution is tailored for applications such as motion capture, fitness tracking, and gesture recognition.

---

## Project Overview

This application utilizes a webcam feed to detect and visualize body landmarks in real time. Key features include:

1. **Facial Landmark Detection**: Captures key facial features for expressions and motion analysis.
2. **Hand Landmark Detection**: Tracks both right and left hand positions and gestures.
3. **Pose Landmark Detection**: Identifies body joints to determine posture and movements.
4. **Customization**: Allows visualization styling through customizable colors, thickness, and radii.

---

## Concepts and Frameworks Used

### 1. **MediaPipe Holistic**
   - **Definition**: MediaPipe Holistic is an end-to-end machine learning pipeline that integrates face, hand, and pose tracking into a single holistic model.
   - **Capabilities**:
     - Facial Landmarks: Over 468 unique points on the face.
     - Hand Landmarks: 21 points per hand.
     - Pose Landmarks: 33 points for full-body posture tracking.

### 2. **OpenCV**
   - **Definition**: OpenCV is a library for real-time computer vision.
   - **Usage in Project**:
     - Captures video from the webcam.
     - Processes images to render landmarks and customize visuals.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nehajagtap/Full-Body-Landmarks-Detection-using-Media-Pipe-Holistic.git
   cd Full-Body-Landmarks-Detection-using-Media-Pipe-Holistic

2. **Create and Activate a Virtual Environment**:
   ```bash
    conda create -n mediapipe-env python=3.8 -y
    conda activate mediapipe-env

3. **Install Dependencies**:
   ```bash
    pip install mediapipe opencv-python
