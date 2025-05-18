# TempleRun_GestureControl
🕹️ Temple Run Hand Gesture Control 🎮
Play Temple Run using just your hand — no keyboard needed! 🖐️🤖

🚀 About the Project
Welcome to Temple Run like you’ve never played before — with no keyboard, just your hand gestures and a webcam! 🎥✋

This interactive project combines Computer Vision 🧠, MediaPipe 🧰, and OpenCV 👁️ with PyAutoGUI to bring a whole new way of controlling Temple Run — using your hand as the controller!

🔍 Demo Preview
🎬 Watch it in action:
Imagine jumping, sliding, and turning — all with simple hand motions!

📹 Demo video is on my linkedin

✨ Features
🖐️ Open Palm → Jump (⬆️ Up Arrow)
✊ Fist → Slide (⬇️ Down Arrow)
👉 Swipe Left / Right → Turn Left / Right (⬅️➡️ Arrows)
📸 Real-time hand tracking via webcam
🧠 Gesture detection powered by MediaPipe
⚡ Instant keypresses using PyAutoGUI

🛠️ Tech Stack
Tech	Usage
🐍 Python	Programming Language
🎯 MediaPipe	Hand tracking solution
📷 OpenCV	Webcam and image processing
🎮 PyAutoGUI	Simulating keyboard presses

🧠 How It Works
Webcam Feed 🎥: Captures your hand in real-time.
Hand Tracking ✋: MediaPipe identifies landmarks on your hand.
Gesture Recognition 🧠: Python logic detects gestures (open palm, fist, swipe).
Action Mapping ⌨️: PyAutoGUI triggers keypresses to control Temple Run!

📦 Installation
# Clone the repository
git clone https://github.com/yourusername/TempleRun_GestureControl.git
cd TempleRun_GestureControl

# Create a virtual environment (optional)
python -m venv .venv
source .venv/Scripts/activate  # On Windows

# Install dependencies
run python test.py

✅ Gestures Supported
Gesture	Action Triggered
✋ Open Palm	Jump (⬆️)
✊ Fist	Slide (⬇️)
👉 Swipe Right	Turn Right (➡️)
👈 Swipe Left	Turn Left (⬅️)

📁 File Structure
TempleRun_GestureControl/
│
├── temple_run_control.py    # Main script
├── README.md                # This file!
├── requirements.txt         # All required Python packages

🧪 Dependencies
Install them manually (if not using requirements.txt):
pip install opencv-python mediapipe pyautogui

💡 Troubleshooting
❌ Camera not detected?
Check if another app is using your webcam.

⛔ Gesture not recognized?
Ensure your hand is clearly visible with good lighting 💡.

🐌 Laggy experience?
Close other apps using your camera or system resources.

🔗 GitHub Link
👉 temple_run_by_gestures on GitHub






