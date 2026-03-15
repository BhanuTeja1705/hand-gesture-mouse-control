# hand-gesture-mouse-control
Control computer mouse using hand gestures with Python, OpenCV and MediaPipe.
# Hand Gesture Mouse Control

## Description
This project implements a Hand Gesture Mouse Control system using computer vision. 
It allows users to control the computer mouse, system volume, and screen brightness using hand gestures captured through a webcam.

The system uses MediaPipe for hand tracking and OpenCV for real-time image processing. 
By detecting finger positions and movements, the application converts hand gestures into mouse actions such as cursor movement, clicking, scrolling, and system controls.

## Features

- Real-time hand tracking using MediaPipe
- Mouse cursor control using index finger
- Left click gesture
- Right click gesture
- Scroll using finger movement
- Volume control using finger distance
- Screen brightness control using gestures
- Supports two-hand interaction

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- TensorFlow
- Screen Brightness Control
- PyCAW (Windows Audio Control)

## Project Structure
hand-gesture-mouse-control
│
├── main.py
├── requirements.txt
├── README.md

## Installation

1 Clone the repository
git clone https://github.com/BhanuTeja1705/hand-gesture-mouse-control.git

2 Move to project folder


cd hand-gesture-mouse-control


3 Install dependencies


pip install -r requirements.txt


## Run the Project


python main.py


## Gesture Controls

Right Hand:
- Move Index Finger → Move Cursor
- Thumb + Ring Finger → Left Click
- Thumb + Middle Finger → Right Click
- Middle Finger Movement → Scroll

Left Hand:
- Thumb + Index Distance → Volume Control
- Gesture Up → Increase Brightness
- Gesture Down → Decrease Brightness

## Future Improvements

- Add gesture-based keyboard control
- Improve gesture recognition accuracy
- Add GUI for settings
