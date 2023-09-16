# Fundamental Matrix and Camera Parameter Recovery from Images

This repository contains the code and materials for a project focused on recovering the fundamental matrix and camera parameters from two images, "house1.png" and "house2.png." The goal is to establish the relationship between the two cameras and reconstruct the world coordinates of cardinal points on the house.

## Task Description

The project involves the following tasks:

1. **Image Coordinate Extraction**: Extracting image coordinates (xi and x'i) for 10 cardinal points marked in "house1.png" and "house2.png," respectively.

2. **Fundamental Matrix Estimation**: Reconstructing the fundamental matrix (F) relating the two views using the 8-point algorithm.

3. **Triangulation for 3D Reconstruction**: Using the canonical camera pair (Pˆ, Pˆ') and triangulation to reconstruct the 3D coordinates (Xˆi) of the points corresponding to image points xi and x'i.

4. **3D Homography Estimation**: Matching Xˆi with the provided world coordinates Xi and recovering the 3D homography (H) that relates the canonical camera pair (Pˆ, Pˆ') to the correct camera pair (P, P').

5. **World Coordinate Estimation**: Using the correct camera pair (P, P') and triangulation to find the world coordinates (Yj) of points yj and y'j marked in the images.

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed:

- [Python](https://www.python.org/)
- [NumPy](https://numpy.org/)
- [OpenCV](https://opencv.org/)
- [Matplotlib](https://matplotlib.org/)
- [Math](https://docs.python.org/3/library/math.html)

You can install the required Python packages using pip:

pip install numpy opencv-python

### Usage

1. Clone this repository to your local machine:

git clone https://github.com/AriolaLeka/Fundamental-Matrix-and-Camera-Parameter-Recovery.git

2. Navigate to the project directory:

cd Fundamental-Matrix-and-Camera-Parameter-Recovery/Matrix-Camera Recovery.ipynb

## Results
The estimated fundamental matrix (F), camera parameters (P, P'), 3D coordinates (Xˆi), homography matrix (H), and final world coordinates (Yj) can be found in the results.txt/ directory.

## Acknowledgement

This project was done in collaboration with Shega Likaj and Francisco Amoros Cubells.
