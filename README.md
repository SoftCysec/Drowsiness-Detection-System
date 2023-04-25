# Drowsiness-Detection-System

In this Python project, we will be using OpenCV for gathering the images from webcam and feed them into a `Deep Learning` model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’. The approach we will be using for this Python project is as follows :

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.

## Project Prerequisites
The requirement for this Python project is a webcam through which we will capture images. You need to have Python (3.6 and above) installed on your system, then using pip, you can install the necessary packages.

1. *OpenCV* – pip install opencv-python (face and eye detection).
2. *TensorFlow* – pip install tensorflow (keras uses TensorFlow as backend).
3. *Keras* – pip install keras (to build our classification model).
4. *Pygame* – pip install pygame (to play alarm sound).

