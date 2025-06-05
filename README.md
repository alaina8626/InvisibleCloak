# InvisibleCloak

This project recreates the famous "invisibility cloak" effect using Python and OpenCV. By detecting red-colored regions in real-time video feed, the program replaces those regions with a pre-captured static background — creating the illusion of invisibility.

🔍 How It Works
- Background Capture:
Captures a static background image for replacement purposes.

- Color Detection:
Detects red color in the HSV color space using two HSV ranges to cover red’s hue spectrum.

- Mask Creation:
Builds a binary mask where the cloak is detected, then refines it using morphological operations.

- Magic Happens:
Replaces the red-colored cloak region with the background, creating a seamless invisibility illusion.

- Display:
Shows the real-time effect via webcam.

📦 Requirements
- Python 3.x

- OpenCV (pip install opencv-python)

- NumPy (pip install numpy)

🚀 Usage

_python invisible_cloak.py_

Press 'q' to exit the webcam window.

