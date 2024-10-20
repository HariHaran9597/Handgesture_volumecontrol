Volume Control with Hand Gestures using OpenCV & MediaPipe 🎛️🖐️
This project allows you to control your system volume using hand gestures detected through a webcam. It utilizes OpenCV for image processing and MediaPipe for hand tracking, providing an intuitive way to adjust volume levels with simple hand movements.

Features
📸 Real-time Hand Tracking: Uses MediaPipe to detect and track hand landmarks with a webcam.
🎚️ Volume Adjustment: Adjusts system volume based on the distance between your thumb and index finger.
📊 Dynamic Feedback: Displays volume percentage and a visual bar indicating the current volume level.
⚙️ Python & OpenCV Integration: Simple and efficient integration of computer vision libraries for smooth performance.
Tech Stack
Python (v3.x)
OpenCV (v4.x)
MediaPipe (for hand tracking)
pycaw (for controlling audio settings in Windows)
Setup Instructions
Clone the repository:
bash
Copy code
git clone https://github.com/xxxxxxxxxx/volume-control-hand-gestures.git
cd volume-control-hand-gestures
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Run the script:
bash
Copy code
python gvc.py
Usage
Ensure your webcam is connected and running.
Move your thumb and index finger closer or farther apart to decrease or increase the volume.
A circle turns green when the volume is at its minimum level for visual feedback.
Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs or feature suggestions.
