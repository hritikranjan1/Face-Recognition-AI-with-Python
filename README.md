# Face Recognition AI with Python

This project is a simple face recognition system built using Python, OpenCV, and the `face_recognition` library. It detects and recognizes faces from images and webcam feed in real-time.

## Features
- Real-time face recognition from webcam feed.
- Support for multiple known faces (stored in `images/` folder).
- Text-to-speech functionality that announces the recognized face name.

## Setup and Installation

### Prerequisites
- Python 3.x
- `pip` (Python package installer)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hritikranjan1/Face-Recognition-AI.git
   cd Face-Recognition-AI
Install required dependencies:

bash

pip install -r requirements.txt

Place images of the people you want to recognize in the images/ folder.

Run the project:

bash

    python main.py

Dependencies

    opencv-python: for handling image processing.
    numpy: for handling matrix operations.
    face_recognition: for recognizing faces.
    pyttsx3: for text-to-speech functionality.
