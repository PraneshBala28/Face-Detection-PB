# Face Detection using OpenCV

A simple face detection system using OpenCV and Python. The program captures video from the webcam and detects faces in real-time.

![alt text]([http://url/to/img.png](https://github.com/PraneshBala28/Face-Detection-PB/blob/main/FaceDetection.jpg?raw=true))

## Requirements
- Python 3.x
- OpenCV (opencv-python) version 4.10.0.84

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/PraneshBala28/Face-Detection-PB.git
    cd face-Detection-PB
    ```

2. Install the required dependencies:
    ```bash
    pip install opencv-python
    ```

## Usage

1. Run the face detection script:
    ```bash
    python face_detection.py
    ```

2. Press `q` to quit the program.

## Code Explanation

- **Import Libraries:** Import the necessary libraries (`cv2`, `time`).
- **Load Haar Cascade:** Load the pre-trained Haar cascade for face detection.
- **Setup Video Capture:** Initialize the webcam and set the resolution.
- **Frame Processing:** Convert each frame to grayscale and detect faces.
- **Draw Rectangles:** Draw rectangles around detected faces.
- **Display FPS:** Calculate and display the frame rate.
- **Exit:** Release the capture and close windows when `q` is pressed.

---

*Project by Pranesh Balaji.*
