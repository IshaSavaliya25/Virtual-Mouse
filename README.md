# 🖐️ Hand Gesture Mouse Controller

A Python-based gesture recognition system that allows you to control your mouse using hand gestures via webcam. It uses MediaPipe for real-time hand tracking, and PyAutoGUI for mouse interaction, enabling actions such as mouse movement, left-click, right-click, double-click, screenshot, and volume control.



## 🚀 Features

- 🖱️ Move mouse pointer using your index finger
- 👆 Left Click
- 👉 Right Click
- 👆👈 Double Click
- ✌️ Take Screenshot
- 🔊 Adjust Volume using pinch gesture
- (Optional) 🔆 Adjust Brightness (code included, commented)

---

## 🧠 How It Works

- Uses MediaPipe to detect 21 hand landmarks
- Calculates finger angles and distances to detect gestures
- Maps index finger movement to cursor movement
- Detects gestures for different mouse actions and volume control

---

## 🛠️ Tech Stack

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- pynput
- NumPy
- pycaw (for volume control)
- screen-brightness-control (optional)

---

## 📁 Project Structure

```bash
gesture_mouse/
├── main.py               # Main script to run the gesture controller
├── util.py               # Utility functions for angle & distance calculations
├── requirements.txt      # Required Python libraries
├── screenshots/          # Folder for captured screenshots
└── README.md             # Project documentation
