# Fabric Defect Detection

This project aims to detect fabric defects using computer vision techniques with the help of OpenCV library. The defects are identified by applying various image processing steps such as grayscale conversion, blurring, denoising, binary conversion, erosion, dilation, and contour detection. The application also provides a user-friendly interface for uploading fabric images and visualizing the results using Streamlit.

## Prerequisites

Make sure you have the following dependencies installed:

- Python
- OpenCV
- Streamlit

## You can install the dependencies by running the following command:

pip install opencv-python streamlit

## For running the code:

streamlit run main.py

## Implementation Details:
The main.py file contains the implementation of fabric defect detection. It performs the following steps on the input fabric image:

Convert the image to grayscale.
Apply blurring to reduce noise.
Apply denoising techniques if required.
Convert the image to binary using an appropriate threshold value.
Perform erosion and dilation operations to improve the defect detection.
Detect contours in the image.
Draw contours around the detected defects.
This file contains the Streamlit application code that integrates the fabric defect detection implementation and provides the user interface for uploading images and visualizing the results.

## Author: Zaoyad Khan Raad

