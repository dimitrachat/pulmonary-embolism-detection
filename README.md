# pulmonary-embolism-detection
A project using traditional computer vision techniques to detect pulmonary embolisms in CT scans
# Pulmonary Embolism Detection Using Traditional Computer Vision Techniques

## Overview
This project implements a computer vision system for detecting pulmonary embolisms in CT scans. It uses traditional image processing methods such as grayscale conversion, threshold filtering, Hough Circle detection, Gaussian blur, connected components analysis, and morphological operations (erosion & dilation) to isolate and detect embolisms.

## Background
Pulmonary embolism (PE) is a blood clot that blocks the pulmonary artery. Early detection is critical for saving lives. 

## Key Features
- **Image Pre-processing:** Converts CT scan slices (NRRD files) to grayscale to reduce complexity.
- **Region Identification:** Detects the main pulmonary artery and ascending thoracic aorta using the Hough Circles method.
- **Segmentation:** Applies thresholding, cropping, and connected components analysis to isolate the region of interest.
- **Embolism Detection:** Utilizes morphological operations and band thresholding to highlight embolisms.
- **Performance:** Achieves over 90% accuracy in correctly classifying negative cases and detects about 70% of embolisms in positive cases.

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- NumPy
- (Additional libraries such as matplotlib can be added as needed)

## Usage
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/yourusername/pulmonary-embolism-detection.git
