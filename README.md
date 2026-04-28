# Hand Tracker (MediaPipe + OpenCV)

## Overview

This project is a simple real-time hand tracking application using MediaPipe and OpenCV. It captures video from the webcam, detects a hand, and visualizes the 21 hand landmarks along with their connections (hand skeleton).

## Features

* Real-time webcam hand detection
* 21 landmark points per hand
* Skeleton visualization of hand structure
* Lightweight and fast execution

## Requirements

* Python 3.10+
* OpenCV
* MediaPipe

## Installation

Install dependencies using pip:

```bash
pip install opencv-python mediapipe
```

## Usage

Run the main script:

```bash
python python.py
```

Press **ESC** to exit the application.

## How it works

* Captures frames from webcam
* Converts frames to RGB for MediaPipe processing
* Detects hand landmarks
* Draws landmarks and connections on the frame
* Displays live video output

## Future improvements

* Add gesture recognition
* Calculate finger angles
* Add biomechanical constraints (ligaments simulation)
* Multi-hand tracking support

## License

Free to use for learning and personal projects.
