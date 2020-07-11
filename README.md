# Covid19-Mask-Detector

## Description
Our goal is to train a custom deep learning model to detect whether a person is or is not wearing a mask.
This detector can be used to ensure the sefety of the people.
It can be used in real time systems for detecting whether people are wearing mask or not


## Table of Contents
  1. Usage
  2. Implementation
  
      
### 1. Usage
 1. First run the train_mask_detector.py file in the experiements folder by specifying the path of the dataset
 2. Use the model in the detect_mask_video.py for detecting whether the person has a mask or not on his face

### 2. Implementation of COVID19 Mask Detector with OpenCV, Keras and Deep Learning

The model is made in two phases:
1. Train the face mask detector model
2. Apply the face mask detector model

train_mask_detector.py: Accepts our input dataset and fine-tunes MobileNetV2 upon it to create our mask_detector.model.

plot.png : A training history plot.png containing accuracy/loss curves is also produced.

detect_mask_image.py: Performs face mask detection in static images.

detect_mask_video.py: Using your webcam, this script applies face mask detection to every frame in the stream.

