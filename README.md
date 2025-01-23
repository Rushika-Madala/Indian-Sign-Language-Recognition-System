# Indian Sign Language (ISL) Recognition System

## Project Overview

Sign language serves as a primary medium of communication for individuals who are hearing or speech impaired. In recent years, considerable advancements have been made in translating American Sign Language (ASL) to text, but meagre developments have taken place to aid Indian Sign Language (ISL) users. India, is one of the largest deaf community globally. Some efforts have been made in Indian Sign Language Recognition (SLR) but are limited to alphanumeric gesture recognition. Real-Time Sign Language translation is an essential yet challenging task as sign language uses fast and complex hand movements, posture adjustments, and facial expressions. 
 
The proposed model is a real-time Indian Sign Language to-text translator to bridge this gap in existing SLR models. This approach is to develop a Computer Vision model utilizing techniques and methods such as pose estimation, feature extraction, image segmentation, edge detection, and image classification to identify, extract, and interpret the ISL gestures used by the users and accurately classify them into the corresponding English text. The impact of this work could be crucial in extending and drastically improving current language aids for the speech or hearing impaired as it would reduce the barrier of understanding Indian Sign Language to communicate effectively with non-ISL users.   



## Features
- Real-time hand gesture recognition
- Uses MediaPipe for holistic pose estimation
- Supports multiple sign language gestures
- Visualization of hand landmark detection
- Displays the identified sign as text on screen 

## Prerequisites
- Python 3.8+
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib
- MediaPipe

## Installation
1. Clone the repository
2. Install required dependencies:
```bash
pip install opencv-python numpy matplotlib mediapipe
```

## Dependencies
- `cv2`: Computer vision and image processing
- `numpy`: Numerical computing
- `mediapipe`: Hand landmark and pose detection
- `matplotlib`: Data visualization

## Project Structure
- Hand landmark detection using MediaPipe
- Gesture classification 
- Real-time video processing
- Visualization of detected signs

## Usage
1. Open the `ISL_translator.ipynb` notebook
2. Run cells sequentially
3. Ensure webcam is connected for real-time gesture recognition

## Limitations
- Requires good lighting conditions
- Accuracy depends on hand visibility
- Limited to predefined gesture set

## Future Improvements
- Expand gesture recognition vocabulary
- Improve machine learning model accuracy
- Add speech synthesis for translated signs

## Acknowledgments
- MediaPipe by Google
- OpenCV Community