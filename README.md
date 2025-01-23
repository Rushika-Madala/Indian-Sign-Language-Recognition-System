# Indian Sign Language (ISL) Translator

## Project Overview
This Jupyter notebook implements an Indian Sign Language (ISL) translator using computer vision and machine learning techniques. The project aims to bridge communication gaps by translating hand gestures into text or speech.

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
- Machine Learning Research Team
