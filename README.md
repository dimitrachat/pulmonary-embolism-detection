# pulmonary-embolism-detection

## Overview
This project aims to automate the detection of Pulmonary Embolism (PE) in Computed Tomography Pulmonary Angiograms (CTPAs) using traditional computer vision techniques. The goal is to isolate and detect embolisms in the main pulmonary artery, improving accuracy and efficiency in medical diagnostics. It uses traditional image processing methods such as grayscale conversion, threshold filtering, Hough Circle detection, Gaussian blur, connected components analysis, and morphological operations (erosion & dilation) to isolate and detect embolisms.

## Motivation
Pulmonary Embolism (PE) is a life-threatening condition where a blood clot blocks the pulmonary artery. This project applies computer vision techniques to detect PE in CTPA scans, reducing human error and improving diagnostic speed. Early detection is critical for saving lives.

## Methods
The project uses the following techniques:
- Grayscale conversion
- Threshold filtering
- Hough Circles for circle detection
- Gaussian blur
- Connected Components Analysis (CCA)
- Erosion & Dilation
- Band thresholding
  
## Results
The algorithm achieved:
- Over 90% accuracy in classifying negative patients.
- Approximately 70% accuracy in detecting embolisms in positive cases.

## Conclusion
The project demonstrates the potential of computer vision in medical diagnostics, particularly in PE detection. While the results are promising, further improvements can be made by incorporating deep learning techniques and annotated datasets.

## Future Work
- Implement deep learning models for improved accuracy.
- Create an annotated dataset for better training and validation.
- Extend the application to other medical imaging tasks, such as cancer detection or bone fracture diagnosis.

## References
- Blackmon, K. N., et al. (2011). Computer-aided detection of pulmonary embolism at CT pulmonary angiography.
- Bouma, H., et al. (2009). Automatic detection of pulmonary embolism in CTA images.
- Chan, H.-P., et al. (2008). Computer-aided diagnosis of lung cancer and pulmonary embolism.

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- NumPy
- (Additional libraries such as matplotlib can be added as needed)
