# Fatigue_Detection_Project
Periodically captures the user's face and detects the level of fatigue using a CNN, then recommends a break accordingly.

## Technologies Used
- Python
- TensorFlow
- Keras
- Jupyter Notebook

## How It Works
- Captures a 5 second video every 30 minutes
- One algorithm determines length of time eyes are open and returns binary output of tiredness
- Second algorithm runs CNN on each captured frame, then returns binary output of tiredness
- Combines model outputs to determine overall fatigue level and recommend breaks of different lengths

## Purpose
Built as a senior computer science project focused on solving real world issues.  Our goal was to reduce burnout of at-home workers.

## File Descriptions
TiredDetectionFinal.ipynb - The main function of the project.  This file incorporates everything and displays the user interface.  
It contains the functions for both tired detection tests.

TiredDetectCNN.ipynb - The file where the CNN is created and trained.  This file contains the code to train the CNN and has it being 
tested on a few images.  At the end of the file, the early stages of the webcam capture and eye detection can be seen.

EyeDetectionDemo.ipynb - The code used to detect the user's eyes from the webcam.  This is the original version of this code that 
still contains the window displaying the live feed and predictions.  It is used to demonstrate the eye detection function of the project.  The GUI parts of this code were removed when being implemented into the final file.

## Notes
Dataset and model file not included due to file size limitations.
