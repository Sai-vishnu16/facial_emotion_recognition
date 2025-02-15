# Facial Emotion Recognition

## Overview
The **Facial Emotion Recognition System** is a real-time application that detects human emotions from facial expressions using deep learning techniques. The model classifies facial expressions into seven categories: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

## Features
- **Real-Time Emotion Detection**: Uses a webcam to capture live video and recognize emotions.
- **Deep Learning-Based Model**: Utilizes a pre-trained Convolutional Neural Network (CNN) model for accurate emotion classification.
- **OpenCV Integration**: Uses OpenCV for face detection and video stream processing.
- **User-Friendly Interface**: Displays real-time emotion predictions on video frames.

## Technologies Used
### Software
- **Python Libraries**:
  - `OpenCV`: For real-time face detection and video stream processing.
  - `TensorFlow/Keras`: For deep learning model implementation.
  - `NumPy`: For numerical computations.

### Hardware
- A standard webcam for capturing live video streams.

## How It Works
1. **Face Detection**:
   - Detects human faces using OpenCV's Haar Cascade classifier.
   - Extracts the region of interest (ROI) containing the face.

2. **Preprocessing**:
   - Converts the face ROI to grayscale and resizes it to `48x48` pixels.
   - Normalizes pixel values for better model performance.

3. **Emotion Classification**:
   - Uses a CNN model trained on facial expression datasets.
   - Predicts one of seven emotions for the detected face.

4. **Displaying Results**:
   - Draws bounding boxes around faces.
   - Displays the predicted emotion label in real time.

## Installation
### Clone the Repository
```bash
git clone https://github.com/your_username/facial_emotion_recognition.git
cd Facial_Emotion_Recognition
```

### Download Pre-trained Model
- Place `model.h5` in the project directory.

### Run the Application
```bash
python opencvfer.py
```
