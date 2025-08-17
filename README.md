# virtualcalculator
Virtual calculator using Python,Mediapipe,Opencv-python.
The Virtual Calculator is an interactive application built using Python, OpenCV, and MediaPipe that allows users to perform basic arithmetic operations (addition, subtraction, multiplication, division) using hand gestures instead of pressing physical keys.

🔹 How It Works:

Hand Tracking with MediaPipe

MediaPipe detects and tracks the position of hand landmarks (like fingertips, joints, etc.) in real time.

It identifies which fingers are raised or touching.

OpenCV for Video Processing

OpenCV captures video from the webcam.

It overlays a virtual calculator interface (buttons for digits and operators) on the video feed.

When a finger touches a specific region (a calculator button), it is considered a "press."

Gesture-Based Input

Example: Touching a number button with the index finger inputs that number.

Pinching fingers or specific gestures can be mapped to "Enter" or "Clear."

Display & Calculation

The pressed keys are displayed on the screen.

A simple Python math expression evaluator performs calculations.

The result is shown in real time on the virtual display.

🔹 Features:

Hands-free, touchless calculator.

Detects hand gestures to select numbers and operations.

Works in real-time with any standard webcam.

Easy to extend (e.g., add scientific functions, history).

🔹 Tech Stack:

Python → core programming language.

OpenCV → for image capture, display, and UI overlay.

MediaPipe Hands → for real-time hand landmark detection and gesture tracking.
