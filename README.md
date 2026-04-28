# Face Mask Detection

## Project Overview
Developed a Face Mask Detection system that identifies whether a person is wearing a mask or not using Computer Vision and Deep Learning.

## Key Features
- Detects faces and classifies as Mask / No Mask
- Works under different lighting conditions, angles, and backgrounds
- Improved model generalization using data augmentation

## Technologies Used
- Python
- OpenCV
- TensorFlow
- NumPy
- Colab

## Dataset Preparation
Collected and cleaned a dataset containing mask and no-mask images.

Performed preprocessing steps:
- Resized images to fixed dimensions
- Normalized pixel values
- Balanced dataset classes

Applied data augmentation:
- Rotation
- Horizontal flip
- Brightness adjustment
- Zoom variations

## CNN Model Architecture
The model was built using Convolutional Neural Networks (CNN) with:

- Multiple Conv2D layers with ReLU activation for feature extraction
- MaxPooling layers for dimensionality reduction
- Dropout layers to reduce overfitting
- Fully Connected Dense layers
- Softmax output layer for classification

## Model Performance
- Accuracy improved by approximately 15% after applying augmentation and hyperparameter tuning.
- Achieved reliable predictions on unseen images.

pip install opencv-python tensorflow numpy matplotlib
