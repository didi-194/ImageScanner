# ImageScanner
implementation of an image scanner using OpenCV (cv2) and NumPy

# Image Scanner using OpenCV and Python

This Python script implements an image scanner using the OpenCV library. It can process images from either a live webcam feed or from a specified image file. The scanner performs various image processing techniques to detect contours, identify the largest contour, and create a scanned-like perspective view of the detected object.

## Features

Webcam Feed or Image File: Choose between using a live webcam feed or inputting an image file for scanning.
Contour Detection: Detects contours in the image using OpenCV's contour detection functionality.
Perspective Transformation: Applies perspective transformation to obtain a bird's eye view of the largest detected contour.
Adaptive Thresholding: Enhances the scanned image using adaptive thresholding techniques.
Save Scanned Images: Provides the option to save the processed image by pressing the 's' key.
Usage

## Prerequisites
Python 3.x
OpenCV (cv2)
NumPy
Instructions
Clone this repository to your local machine.
Ensure the necessary prerequisites are installed.
Run the Python script (image_scanner.py).
Follow the on-screen prompts to choose between using a webcam feed or an image file.
If using an image file, place the file in the same directory as the script.
Press the 's' key to save the scanned image.
Code Overview

The code performs the following tasks:

Initializes settings for webcam feed and image dimensions.
Accepts user input to determine the source of the image (webcam or file).
Processes the image: converts to grayscale, applies edge detection, contour identification, and perspective transformation.
Displays the processed images at different stages for visual inspection.
Offers the functionality to save the processed image.
Contributions

Contributions and improvements are welcome! Feel free to submit issues or pull requests to enhance the functionality or optimize the code.

License

This project is licensed under the MIT License.
