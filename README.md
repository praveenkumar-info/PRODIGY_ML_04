
# Hand Gesture Recognition using Python, OpenCV, MediaPipe, and TensorFlow

This repository contains code for a real-time hand gesture recognition system using Python. The system detects and classifies different hand gestures from a webcam feed.

## Prerequisites

- Python 3.x
- OpenCV
- NumPy
- MediaPipe
- TensorFlow
- Trained hand gesture recognition model (`mp_hand_gesture`)
- Class names file (`gesture.names`)

## Installation

1. Install Python if you haven't already.
2. Install required packages using pip:

```bash
pip install opencv-python numpy mediapipe tensorflow
```
## Usage
1. Clone this repository or download the code files.
2. Place the trained model (mp_hand_gesture) and class names file (gesture.names) in the same directory as the script.
3. Run the hand_gesture_recognizer.py script:
```bash

python hand_gesture_recognizer.py
```
1. The webcam will open, and the system will start recognizing hand gestures in real-time.
2. Press the 'q' key to exit the program.
## Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests to improve this project.
