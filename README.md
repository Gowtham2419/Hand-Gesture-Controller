# Hand Gesture Control System

An AI-powered virtual mouse system that allows users to control their PC using hand gestures through a webcam.

Built using Python, OpenCV, and MediaPipe.

---

## Features

### Multi-Mode Interaction
- MOVE MODE – Cursor control
- SCROLL MODE – Hand-based scrolling
- PAUSED MODE – Safety mode

### Gesture Controls
- Left Click – Thumb + Index Finger pinch
- Right Click – Thumb + Middle Finger pinch
- Scroll – Two finger gesture
- Pause – Closed fist

### Safety Features
- Global Kill Switch ('Q')
- Auto Pause on hand loss
- Gesture cooldown protection

### Visual Dashboard
- Live FPS display
- Current mode display
- Gesture detection status

---

## Technologies Used
- Python
- OpenCV
- MediaPipe
- PyAutoGUI

---

## Requirements
- Python 3.8+
- Webcam
- hand_landmarker.task model

---

## Installation

### 1. Clone Repository
```bash
git clone https://github.com/Gowtham2419/Hand-Gesture-Controller.git
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Download Model
Download:
https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task

Place the file inside the project folder.

---

## Run Project

```bash
python main.py
```

---

# Gesture Guide

## Move Cursor
Raise only the Index Finger.

## Left Click
Pinch Thumb + Index Finger.

## Right Click
Pinch Thumb + Middle Finger.

## Scroll Mode
Raise Index + Middle Finger.

## Pause
Make a closed fist.

## Quit
Press Q key.

---

## Configuration
Modify values inside `config.py`:
- SCROLL_SPEED
- GESTURE_COOLDOWN
- SMOOTHING_FACTOR

---

## Future Improvements
- Voice Control
- Virtual Keyboard
- Custom Gesture Training
- AI Gesture Learning

---

## Author
Gowtham Makkapati
