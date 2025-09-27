# Computer-Vision-Based-Smart-Typing-Interface
Developed a real-time typing system that detects keyboard keys and a red cap marker using YOLOv8, enabling automated typing with support for letters, numbers, and special keys (Enter, Backspace, Arrow keys). Integrated PyAutoGUI for seamless interaction with active applications like Word Online, achieving hands-free typing through computer vision.

project video link: https://drive.google.com/file/d/19l0zRQJmaFODP4PeP-1bzqBJz2sfGRCY/view?usp=share_link

# Features
Detects a object (e.g., ball) in real-time using computer vision.
Tracks object position to determine virtual key presses.
Prevents duplicate key presses when the object stays on the same key.
Supports dynamic mapping to a virtual keyboard layout.
Works with USB/web cameras or IP cameras.

# Requirements
Python 3.10+
OpenCV (opencv-python)
NumPy (numpy)
PyAutoGUI (pyautogui)
Ultralytics YOLO ( object detection)
Camera (USB webcam or IP camera)

# Workflow:
Place the colored object (e.g., red cap) in front of the camera.
Move it over the virtual keyboard displayed on screen.
The system detects key positions and types corresponding characters.
Duplicate key presses are avoided if the object stays on the same key.
