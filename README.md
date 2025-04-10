# Computer Vision - TA2

This repository contains implementations of various computer vision algorithms as part of the TA2 coursework. The focus is on feature detection, image segmentation, and other foundational techniques in computer vision.

## Table of Contents
- [Introduction](#introduction)
- [Implemented Algorithms](#implemented-algorithms)
- [Prerequisites](#prerequisites)
- [File Structure](#file-structure)
- [References](#references)

## Introduction
The repository demonstrates the implementation of key computer vision algorithms using Python and OpenCV. These algorithms are widely used in tasks such as object detection, image matching, and segmentation.

## Implemented Algorithms
1. **SIFT (Scale-Invariant Feature Transform)**:
   - Detects and describes local features in images.
   - Provides scale and rotation invariance.
   - File: `SIFT/SIFT_Implementation.ipynb`

2. **Shi-Tomasi Corner Detection**:
   - Identifies corners in an image based on intensity variations.
   - Efficient for feature detection in real-world scenarios.
   - File: `Shi-Tomasi/SHitomasi.ipynb`

3. **GrabCut Segmentation**:
   - Implements the GrabCut algorithm for foreground extraction.
   - File: `GrabCut/GrabCut.ipynb` (currently empty, to be implemented).

## Prerequisites
- Python 3.x
- Libraries:
  - OpenCV
  - NumPy
  - Matplotlib

Install the required libraries using:
```bash
pip install opencv-python numpy matplotlib
```

## File Structure
```
CV-TA-2/
├── SIFT/
│   └── SIFT_Implementation.ipynb
├── Shi-Tomasi/
│   └── SHitomasi.ipynb
├── GrabCut/
│   └── GrabCut.ipynb
└── README.md
```

## References
- OpenCV Documentation: https://docs.opencv.org/
- SIFT Paper: Lowe, D. G. (1999). "Object recognition from local scale-invariant features."
- Shi-Tomasi Corner Detection: Shi, J., & Tomasi, C. (1994). "Good features to track."
