cat <<EOL > README.md
# Age and Gender Detection using DeepFace

This project demonstrates how to use the **DeepFace** library along with **OpenCV** to detect faces from a live webcam feed, determine their gender and age range, and keep track of the counts of detected males and females. The system processes real-time video streams, showing age, gender, and counts of male/female detections.

## Features
- **Real-time face detection** using Haar Cascades.
- **Gender and age range prediction** using the DeepFace library.
- **Tracking of unique faces** to avoid duplicate counting.
- **Display of live video feed** with annotated age and gender.
- **Console output** of detected age ranges and gender counts.

## Requirements

- Python 3.10 
- **OpenCV**: For real-time face detection
- **DeepFace**: For analyzing age and gender
- **TensorFlow**: Backend for DeepFace
- **Haar Cascade XML** file for face detection

### Required Python Packages

- `opencv-python-headless`
- `deepface`
- `tensorflow`
- `numpy`
- `Pillow`

## Installation

### 1. Clone the Repository

To get started, clone the repository:

git clone https://github.com/MayuriGhongade/Age-and-Gender-Detection-using-DeepFace.git

# Age and Gender Detection Project

## Installation

### Install Required Packages
Run the following command to install the necessary dependencies:
pip install -r requirements.txt

## Acknowledgments
- [DeepFace Library](https://github.com/serengil/deepface)
- [OpenCV](https://opencv.org/)
- [Haar Cascade](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)

