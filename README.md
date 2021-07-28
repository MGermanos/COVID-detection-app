# COVID-19 Detection
A tool to help healthcare worker identify COVID-19 in X-Ray images

## Table of Contents

- [Overview](#overview)
- [Getting Startrted](#requirements)
  * [Requirements](#requirements)
  * [Usage](#Usage)
  * [Demo](#demo)


## Overview
To help in the fight against the COVID-19 pandemic, we developed a tool that utilizes transfer learning via the convolutional neural network VGG19 to detect the presence of COVID-19 in chest X-Ray images. This tool reads as input chest X-Ray images and returns a diagnosis on whether the patient suffers from COVID-19, pneumonia, or neither.

The architecture of our model used is the VGG-19 model with three fully connected layers appended to it to help with the classification.

## Getting Started
### Requirements
The model and the GUI were built using Python.
- [Python 3.7](https://www.python.org/)
- [wxPython](https://www.wxpython.org/)
- [Tensorflow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)

### Usage
After downloading the program, run the script titled `App.py` and th application will start.
You will see the home page of the application, where simple instructions on how to use the application are written.
Once you click on the button at the bottom of th epage titled `Select image`, a prompt will appear asking for the X-Ray image of the patient.
After selecting the image, the program will use the pre-trained model to make a diagnosis for the patient.
The diagnosis will appear as a pop-up notification.

### Demo

