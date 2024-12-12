# Hand Gesture-Controlled System

## Overview
This project implements a real-time hand gesture recognition system that uses Python, OpenCV, Mediapipe, and PyAutoGUI to control various computer functionalities dynamically. By recognizing predefined hand gestures, the system performs tasks such as adjusting audio volume, screen brightness, and cursor movement.

## Features
- **Real-Time Gesture Recognition**: Tracks and identifies hand gestures using Mediapipe's hand tracking module.
- **Dynamic Gesture Classification**: Utilizes Euclidean distance calculations and logical conditions to classify gestures.
- **Gesture-Based Controls**:
  - Adjust system audio volume.
  - Control screen brightness.
  - Simulate cursor movement and other actions.
- **Modular and Scalable**: Easily extendable to add more gestures and corresponding functionalities.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - OpenCV: For image and video processing.
  - Mediapipe: For hand tracking and landmark detection.
  - PyAutoGUI: For simulating mouse and keyboard actions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-link.git
   cd your-repo-link
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python gesture_control.py
   ```

## Usage
1. Ensure your webcam is connected and functional.
2. Launch the program and allow access to your camera.
3. Perform the predefined gestures in front of the camera to control system functions.
   - Example gestures:
     - **Volume Control**: Open/close hand.
     - **Brightness Adjustment**: Two-finger pinch/spread.
     - **Cursor Movement**: Hand pointing gesture.

## How It Works
1. **Hand Detection**:
   - The Mediapipe library detects and tracks hand landmarks in real-time.
2. **Gesture Recognition**:
   - Euclidean distance calculations are used to measure distances between hand landmarks.
   - Logical conditions classify gestures based on these measurements.
3. **System Interaction**:
   - PyAutoGUI translates recognized gestures into system actions like cursor movement or volume adjustments.

## Directory Structure
```
.
├── gesture_control.py         # Main application script
├── utils/                     # Utility functions and helper scripts
├── requirements.txt           # List of required Python libraries
├── README.md                  # Project documentation
```


## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Submit a pull request.


## Contact
For questions or feedback, feel free to reach out at [aymehta04@gmail.com].
