
🖱️ Virtual Mouse using OpenCV, MediaPipe & PyAutoGUI
A hand gesture-based virtual mouse that uses your webcam to control the cursor and perform click actions. Built with OpenCV for video input, MediaPipe for hand tracking, and PyAutoGUI for GUI control.

📜 Project Description
This project allows you to control the mouse pointer using hand gestures captured by a webcam. The system utilizes:

OpenCV for video capture,

MediaPipe for real-time hand tracking, and

PyAutoGUI to simulate mouse movements and clicks on the screen.

The goal is to provide a hands-free way of interacting with a computer, making it especially useful for accessibility purposes or touchless interfaces.

 VirtualMouse
A hand gesture-based virtual mouse that uses your webcam to control the cursor and perform click actions. Built with OpenCV for video input, MediaPipe for hand tracking, and PyAutoGUI for GUI control. 

⚙️ Features
✋ Hand Gesture Control: Move the cursor by moving your hand.

🖱️ Click Simulation: Perform mouse clicks with specific gestures (e.g., thumb + index finger or fist).

🎯 Real-time Tracking: Efficient and fast hand tracking using MediaPipe.

💻 No Extra Hardware: Just a webcam and your hand!

🔧 Installation
✅ Prerequisites:
Python 3.x installed

pip (Python package installer)

📥 Steps:
Clone the repository:

bash
Copy
Edit
git clone https://github.com/RajaNamdeo13/VirtualMouse.git
cd VirtualMouse
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the project:

bash
Copy
Edit
python virtual_mouse.py
Note: Create a requirements.txt file with the following content if it’s not already present:

Copy
Edit
opencv-python
mediapipe
pyautogui
🎥 Demo
(Coming soon: Add a screen recording or GIF of the project in action)

🖥️ How It Works
Your webcam captures live video.

MediaPipe detects and tracks hand landmarks in real-time.

Index finger controls the mouse position.

Specific gestures trigger mouse clicks (e.g., thumb + index = left click).

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you'd like to change.

🙋‍♂️ Author
Raja Namdeo
🔗 GitHub

⭐ Star This Repository
If this project helped you or inspired you, give it a ⭐ on GitHub. It means a lot!
