

# 🧠 Overview

Smart WorkPlay is a futuristic AI-powered system that lets you type and control your computer using football movements.
By combining YOLOv8 and OpenCV, this project tracks your red-cap or foot movements and converts them into keyboard inputs in real-time.

That means you can play football and simultaneously type an email, chat on WhatsApp Web, or write a document — without touching your keyboard.

# The core goal:

“Make technology adapt to your movement — not the other way around.”

# 🌟 Features

⚽ Motion-based Typing: Play football and type messages automatically.

💬 Multi-App Control: Works on Email, WhatsApp Web, Word, Google Docs, etc.

🧠 Smart YOLOv8 Tracking: Detects key positions and your red-cap movement.

🔄 Self-Recalibrating System: Adjusts automatically to lighting or camera shifts.

⌨️ Virtual Keyboard Simulation: Uses PyAutoGUI to press real keys.

🧩 Health + Productivity Fusion: Encourages physical activity while working or chatting.

📊 Live Speed & Accuracy Monitor: See your typing precision and movement speed in real time.

## 🏗️ How It Works
Camera Stream
     ↓
YOLOv8 Model detects:
  • Keyboard keys
  • Red cap (your motion)
     ↓
MotionTracker calculates:
  • Speed
  • Position
  • Direction
     ↓
Keyboard Manager:
  • Simulates typing in WhatsApp, Email, Word, etc.


So, when your red cap moves over a specific key (like “H” or “E”), it types that character automatically on the active window (like Gmail or WhatsApp Web).

# 🧩 Tech Stack
Component	Technology
AI Detection	YOLOv8 (Ultralytics)
Computer Vision	OpenCV
Keyboard Simulation	PyAutoGUI
Language	Python 3.x
Real-time Control	Threading + Numpy




💡 Open WhatsApp Web, Gmail, or Word — and start moving your red-cap or football in front of the camera.
The system will type wherever your cursor is focused.


# 🧠 Vision

Smart WorkPlay aims to redefine multitasking and movement.
It blends health, technology, and creativity — showing that physical motion can power digital actions.


# 🧑‍💻 Author

Kabilan A
AI & Data Science Engineer 

Licensed under the MIT License — free to use, modify, and improve.

# 💬 Acknowledgements

Ultralytics YOLOv8 — Real-time object detection

OpenCV — Video processing

PyAutoGUI — Virtual keyboard simulation
