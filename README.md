# Face Recognition
[![GitHub license](https://img.shields.io/github/license/vinitshahdeo/FaceRecognition.svg)](https://github.com/vinitshahdeo/FaceRecognition/blob/master/LICENSE) ![GitHub followers](https://img.shields.io/github/followers/vinitshahdeo.svg?label=Follow) [![Python 3.5](https://img.shields.io/badge/python-3.5-blue.svg)](https://www.python.org/downloads/release/python-350/)

Face Recognition using Haar-Cascade Classifier, OpenCV, and Python

## Requirements
- Python 3.5
- OpenCV 3.1.0
- Numpy


## Outline

This project consist of 3 parts, which are:

1. Creating datasets (**datasets.py**)
2. Train the model (**training.py**)
3. Recognize faces (**recog.py**)

## Instructions - How to Run ?

 - First run *datasets.py* to generate datasets. Make sure that it creates two folders('datasets' and 'trainer'). The 'datasets' folder contains the grayscale images.
 
 - Supply proper *ID* for the face before running *training.py*.
 
 - Run *recog.py* and don't forget to set each person's face to unique ID.
 
 - If you have more face to be include, change the ID and run the code again.