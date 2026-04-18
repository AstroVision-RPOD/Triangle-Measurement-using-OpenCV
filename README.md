# Triangle Measurement using OpenCV

This repository contains our implementation of OpenCV-based tasks related to triangle detection, measurement, and camera calibration as part of our project work.

##  Objective

The goal of this work is to understand fundamental concepts in computer vision and pose estimation by:

- Detecting geometric shapes (triangle)
- Extracting corner points and edges
- Measuring dimensions from camera input
- Understanding camera properties through calibration

---

##  Tasks Performed

### 1. Triangle Detection (Planar Surface)
- Printed an equilateral triangle on an A4 sheet
- Captured video using laptop camera under varying lighting conditions
- Detected:
  - Edges
  - Lines
  - Corner points
- Implemented using OpenCV in a single Python script

---

### 2. Triangle Detection (Non-Planar Surface)
- Affixed the triangle to a curved surface (cylindrical object)
- Repeated detection process
- Observed effects of surface curvature on detection accuracy

---

### 3. Measurement and Coordinates
- Extracted pixel coordinates of triangle corners
- Computed side lengths in pixel space
- Converted measurements to real-world units using scaling

---

### 4. Camera Calibration
- Performed calibration using checkerboard pattern
- Estimated:
  - Intrinsic parameters (camera matrix)
  - Distortion coefficients
- Studied how camera properties affect measurements

Reference:
https://learnopencv.com/camera-calibration-using-opencv/

---

## Results

- Output videos showing:
  - Edge detection
  - Corner detection
  - Triangle tracking under varying lighting conditions
- Stored in `/videos` folder


---

## Technologies Used

- Python
- OpenCV
- NumPy

---
