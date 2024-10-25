# Hackathon-Language-Interpretation

## Overview

The **Hackathon-Language-Interpretation** project aims to facilitate communication through gesture recognition using computer vision techniques. By leveraging MediaPipe and custom classifiers, this project interprets hand gestures in real time, allowing for potential applications in accessibility, education, and interactive technology.

## Features

- **Real-time Hand Gesture Detection**: Captures and processes hand gestures using a webcam.
- **Gesture Classification**: Identifies specific gestures and classifies them using trained models.
- **Data Logging**: Provides functionality to log gesture data for further analysis or training.
- **User-Friendly Interface**: Displays gesture information and status on the video feed.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Other dependencies specified in `requirements.txt`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AKhilRaghav0/Hackathon-Language-Interpretation.git
   cd Hackathon-Language-Interpretation
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Make sure you have a webcam connected to your computer.

## Usage

1. Run the main script:
   ```bash
   python main.py --device 0
   ```

   You can modify the parameters for width, height, and confidence thresholds.

2. Follow the on-screen instructions to log gestures. Use the keyboard to switch modes and stop the program.

## Key Functions

- **Gesture Detection**: Utilizes MediaPipe to detect hand landmarks and classify gestures.
- **Data Logging**: Captures and logs gestures to CSV files for analysis.
- **Visual Feedback**: Displays detected gestures and additional information on the screen.

## Images

![Gesture Detection Example 1](https://i.postimg.cc/Vk15TCwH/image.png)
*Example of gesture detection in action.*

![Gesture Detection Example 2](https://i.postimg.cc/CKR06hRQ/image.png)
*Detailed view of hand landmarks and gesture classification.*


## Acknowledgments

- [MediaPipe](https://google.github.io/mediapipe/) for powerful hand tracking capabilities.
- OpenCV for image processing functionalities.


