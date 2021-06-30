# COVID-19 Detection
A tool to help healthcare worker identify COVID-19 in X-Ray images

## Table of Contents

- [Overview](#overview)
- [Getting Startrted](#requirements)
  * [Requirements](#sub-heading)
  * [Usage](#Usage)
  * [Demo](#demo)
- [Acknoledgements](#acknowledgements)


## Overview
To help in the fight against the COVID-19 pandemic, we developed a tool that utilizes transfer learning via the convolutional neural network VGG19 to detect the presence of COVID-19 in chest X-Ray images. This tool reads as input chest X-Ray images and returns a diagnosis on whether the patient suffers from COVID-19, pneumonia, or neither.

The architecture of our model used is the VGG-19 model with three fully connected layers appended to it to help our classification.
