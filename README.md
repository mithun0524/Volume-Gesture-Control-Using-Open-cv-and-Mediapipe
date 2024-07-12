# Volume Gesture Control using OpenCV and MediaPipe

## Project Description

Volume Gesture Control is a project that allows users to control the volume of their system using hand gestures. By utilizing OpenCV and MediaPipe, the application can detect specific hand gestures involving two fingers to increase or decrease the volume.

## Features

- **Gesture Recognition**: Detects hand gestures using OpenCV and MediaPipe.
- **Volume Control**: Adjusts system volume based on recognized gestures.
- **Real-Time Processing**: Processes video input in real-time for immediate feedback.

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/mithun0524/Volume-Gesture-Control-Using-Open-cv-and-Mediapipe.git
   cd volume-gesture-control
   ```

2. **Create and activate a virtual environment** (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required dependencies**:
   ```sh
   1. open-cv
   2. mediapipe
   3. pycaw
   ```

## Usage

1. **Run the application**:
   ```sh
   python VolumeGesture.py
   ```

2. **Use the following gestures**:
   - **Decrease Volume**: Move two fingers closer together.
   - **Increase Volume**: Move two fingers farther apart.

## Technologies Used

- **OpenCV**: For video capture and image processing.
- **MediaPipe**: For hand tracking and gesture recognition.
- **Python**: Programming language used for development.
