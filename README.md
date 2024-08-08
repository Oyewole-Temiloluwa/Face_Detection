# Face Detection Project

## Overview
The Face Detection Project uses computer vision techniques to detect faces in images and video streams. This project is useful for various applications including security systems, user authentication, and human-computer interaction.

## Features
- Real-time face detection
- Modular design for easy integration
- Visual feedback through a webcam feed

## Requirements
- Python 3.x
- OpenCV

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/Oyewole-Temiloluwa/Face_Detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Face_Detection
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Files

### FaceDetectionBasics.py
This script demonstrates the basics of face detection using OpenCV. It captures video from the webcam, processes the frames to detect faces, and displays the results in real-time.

### FaceDetectionModule.py
This module contains the face detection functionalities. It uses OpenCV to detect faces in images and provides utilities for integrating face detection into other projects.

## Usage
1. Ensure you have a webcam connected to your computer.
2. Run the basic face detection script:
    ```bash
    python FaceDetectionBasics.py
    ```
3. A window will open showing the webcam feed with face detection functionalities.

## How It Works
1. The `FaceDetectionModule.py` uses OpenCV to detect faces in images.
2. The `FaceDetectionBasics.py` script captures video frames from the webcam, processes these frames to detect faces using the module, and displays the detected faces in real-time.

## Contributing
Feel free to fork this repository, make your changes, and submit a pull request. Contributions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The OpenCV library for providing the computer vision functionalities.
