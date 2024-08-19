# License-Plate-Recognition

This project is a simple license plate detection system implemented in Python using OpenCV, EasyOCR, and Matplotlib libraries.

## Introduction

The goal of this project is to develop a system that can detect license plates in images and extract the license plate numbers from the detected plates. The system uses computer vision techniques for image processing and optical character recognition (OCR) for extracting text from the detected license plates.

## Key Steps

1. **Image Input**: The system takes an input image containing vehicles with license plates.

2. **License Plate Detection**: OpenCV is used to detect the location of license plates within the image using image processing techniques such as edge detection and contour analysis.

3. **License Plate Recognition**: EasyOCR is employed to recognize and extract the text from the detected license plates.

4. **Result Visualization**: Matplotlib is used to visualize the original image with the detected license plates and the extracted license plate numbers.

## Tech Stak

- Language : Python 3.10
- Libraries :
    - OpenCV
    - EasyOCR
    - Matplotlib

You can install these libraries using pip:
```bash
pip install opencv-python
pip install easyocr
pip install matplotlib
```


