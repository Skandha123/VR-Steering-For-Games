VR Steering Simulator 🚗💨
Transform your webcam into a motion-controlled steering wheel for PC racing games!

This Python-based project uses real-time hand/object tracking (via webcam) to simulate keyboard or mouse inputs, allowing you to control racing/driving games with physical steering movements—no VR headset or expensive hardware required!

✨ Features
🎮 Motion-to-Input Control – Steer by rotating hands/objects in front of your webcam.

🖥️ Cross-Game Compatibility – Works with most racing games (e.g., Euro Truck Simulator 2, Forza Horizon, F1 22).

⚙️ Adjustable Sensitivity – Fine-tune steering dead zones & response curves.

⌨️ Multi-Input Support – Simulates keyboard, mouse, or direct gamepad inputs.

📸 No Extra Hardware – Just a standard webcam + Python!

🛠️ Tech Stack
Computer Vision: OpenCV (cv2) + cvzone (for hand/object tracking)

Input Simulation: PyAutoGUI / PyDirectInput (for accurate low-latency inputs)

Hotkey Control: pynput / keyboard (for dynamic keybinding)

Python 3.x – Lightweight and easy to modify.

🚀 Quick Start
Clone & Install:

bash
Copy
git clone https://github.com/yourusername/vr-steering-simulator.git
cd vr-steering-simulator
pip install -r requirements.txt
Run the Detector:

bash
Copy
python main.py
Calibrate & Play!

Position your hands (or a steering wheel prop) in view of the webcam.

Adjust settings in config.py for sensitivity & keybinds.

🎮 Supported Games
✔ Euro Truck Simulator 2
✔ Forza Horizon 4/5
✔ F1 22
✔ BeamNG.drive
✔ Any game with keyboard/mouse steering!

📌 Future Ideas
Head-tracking support (for leaning movements).

Custom gesture controls (e.g., indicators, handbrake).

Machine learning refinement for smoother steering.

Contributions welcome! 🛠️
