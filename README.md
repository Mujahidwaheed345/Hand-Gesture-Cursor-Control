# Hand-Gesture-Cursor-Control


AirPointer is a real-time hand gesture-based cursor control system using MediaPipe and PyAutoGUI. It allows users to control the mouse cursor, click, and scroll using hand gestures detected via a webcam.

Features

Cursor Control: Move the mouse pointer using your index finger.

Click Gesture: Pinch (Thumb + Index Finger) to perform a click.

Scroll Gesture: Pinch (Index + Middle Finger) to scroll up/down.

Webcam Persistence: The webcam remains open unless manually closed by pressing 'q'.

Requirements

Make sure you have the following dependencies installed:

pip install opencv-python mediapipe pyautogui numpy

How to Run
Run the script

python airpointer.py

Usage

Move Cursor: Move your index finger to control the cursor position.

Click: Bring thumb and index finger close together to perform a click.

Scroll:

Move index and middle finger close together.

Move index finger below middle finger to scroll down.

Move index finger above middle finger to scroll up.

Exit: Press 'q' to close the application.

Troubleshooting

Webcam Not Detected?

Ensure your camera is connected and not being used by another application.

Restart the script and check the console for messages.

Cursor Not Moving?

Ensure your hand is properly visible and well-lit.

Try adjusting the camera angle for better tracking.

Future Improvements

Add multi-hand support.

Implement gesture-based right-click and drag.

Improve click and scroll sensitivity.

License

This project is licensed under the MIT License.

Enjoy hands-free control with AirPointer! 🚀
