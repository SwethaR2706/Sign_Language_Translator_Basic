# Sign Language Translator (Computer Vision + Deep Learning)

A real-time hand gesture recognition system that translates basic sign language gestures using a webcam and a trained deep learning model.

## Features
- Real-time hand gesture detection using webcam
- Recognizes multiple sign language gestures
- Deep learning model trained using Keras
- Hand tracking using OpenCV and cvzone
- Displays predicted sign in real time

## Tech Stack
- Python
- OpenCV
- cvzone
- TensorFlow / Keras
- NumPy
- MediaPipe

## How it Works
1. Webcam captures hand gestures in real time
2. Hand is detected using cvzone hand tracking
3. Image is cropped and preprocessed
4. Preprocessed image is passed to the trained Keras model
5. Model predicts the corresponding sign
6. Predicted sign is displayed on the screen

## Supported Gestures
- Hello
- Help
- No
- Sorry
- Thank You
- Yes

## Run the Program

Install dependencies:

pip install -r requirements.txt

Run the translator:

python test.py

## Project Structure

Sign-Language-Translation
│
├── Data
│   ├── Hello
│   ├── Help
│   ├── No
│   ├── Sorry
│   ├── Thank You
│   └── Yes
├── Model
│   ├── keras_model.h5
│   └── labels.txt
│
├── datacollection.py
├── test.py
├── requirements.txt
└── README.md
