# Fabric Defect Detection using OpenCV and Streamlit

This project aims to detect fabric defects using computer vision techniques with the help of OpenCV library. The defects are identified by applying various image processing steps such as gray scaling, blurring, denoising, binary conversion, erosion, dilation, and contour detection. The application also provides a user-friendly interface for uploading fabric images and visualizing the results using Streamlit.

## Prerequisites

Make sure you have the following dependencies installed:

- Python 3.x
- OpenCV
- Streamlit

You can install the dependencies by running the following command:

## Implementation Details
The fabric_defect_detection.py file contains the implementation of fabric defect detection. It performs the following steps on the input fabric image:

1- Convert the image to grayscale.

2-Apply blurring to reduce noise.

3- Apply denoising techniques if required.

4- Convert the image to binary using an appropriate threshold value.

5- Perform erosion and dilation operations to improve the defect detection.

6- Detect contours in the image.

7-Draw contours around the detected defects.

This file contains the Streamlit application code that integrates the fabric defect detection implementation and provides the user interface for uploading images and visualizing the results.
