# Coin Detection using OpenCV

This project demonstrates basic image processing and blob detection using OpenCV and Matplotlib in Python.
It takes an image of coins, processes it through various computer vision steps, and finally detects and counts the number of coins present in the image.

# Features

•	Read and display an image using OpenCV
•	Convert the image to grayscale
•	Split the image into RGB color channels
•	Perform thresholding to create a binary mask
•	Apply erosion and dilation (morphological operations)
•	Detect blobs (coins) using OpenCV’s SimpleBlobDetector
•	Display the intermediate steps and final results using Matplotlib

# Concepts Used

•	Grayscale conversion: Simplifies image data for processing
•	Thresholding: Converts grayscale image to binary for segmentation
•	Morphological operations: Refine the binary image to remove noise
•	Blob detection: Identify circular coin-like objects based on shape and intensity

# Requirements

Make sure you have the following Python packages installed:
pip install opencv-python matplotlib numpy

# How to Run

1.	Clone this repository:
2.	git clone https://github.com/yourusername/coin-detection-opencv.git
3.	cd coin-detection-opencv
4.	Open the Jupyter Notebook:
5.	jupyter notebook
6.	Run the notebook cells sequentially.
Make sure you update the image filename (e.g. coins.jpg) in the code.

# Example Output

•	Original image
•	Grayscale image
•	RGB channel split (R, G, B)
•	Thresholded image
•	Eroded and Dilated images
•	Blob detection with coin count
