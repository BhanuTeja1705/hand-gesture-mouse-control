# 🖐️ Hand Gesture Mouse Control

A computer vision-based system that enables users to control the mouse, system volume, and screen brightness using hand gestures captured through a webcam.

---

## 🚀 Key Features

- 🖐️ Real-time hand tracking using MediaPipe
- 🖱️ Cursor control using index finger movement
- 👆 Left and right click gestures
- 🔄 Scroll functionality using finger movement
- 🔊 Volume control using finger distance
- 💡 Screen brightness control using gestures
- 🤲 Supports two-hand interaction

---

## 🧠 Project Overview

This project uses computer vision techniques to replace traditional input devices like a mouse.

By tracking hand landmarks and finger positions, the system converts gestures into system-level controls such as cursor movement, clicking, scrolling, volume adjustment, and brightness control.

---

## 🛠️ Tech Stack

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- TensorFlow
- PyCAW (Windows Audio Control)
- Screen Brightness Control

---

## 📂 Project Structure

```bash
hand-gesture-mouse-control/
├── main.py              # Main application file
├── requirements.txt     # Dependencies
├── README.md            # Documentation
```
## ⚙️ Installation

### Clone the repository
```bash
git clone https://github.com/BhanuTeja1705/hand-gesture-mouse-control.git
```
Navigate to the project folder
```bash
cd hand-gesture-mouse-control
```
Install dependencies
```bash
pip install -r requirements.txt
```
▶️ Run the Project
```bash
python main.py
```
## 🎯 Gesture Controls

✋ Right Hand

👉 Index Finger → Move Cursor

👍 Thumb + Ring Finger → Left Click

👍 Thumb + Middle Finger → Right Click

✌️ Middle Finger Movement → Scroll

✋ Left Hand

🤏 Thumb + Index Distance → Volume Control

⬆️ Gesture Up → Increase Brightness

⬇️ Gesture Down → Decrease Brightness

📈 Future Improvements

⌨️ Add gesture-based keyboard control

🎯 Improve gesture detection accuracy

🖥️ Add GUI for customization

🤖 Integrate AI-based gesture recognition

## 👨‍💻 Author


Goriparthi Bhanu Teja

⭐ Support

If you like this project, give it a star!
