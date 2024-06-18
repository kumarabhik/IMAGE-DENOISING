# IMAGE-DENOISING
##OVERVIEW

This repository contains the code for training a U-Net-based deep learning model designed to enhance low-resolution images to high-resolution images. The model is trained using paired datasets of low and high-resolution images and leverages TensorFlow and Keras libraries for constructing and training the neural network. The provided code encompasses all necessary steps, including data preprocessing, model definition, training, and evaluation, ensuring a comprehensive framework for image resolution enhancement.

## Requirements
- Python 3.x
- OpenCV
- Numpy
- TensorFlow
- Keras
- Scikit-Image
- TQDM
- Scikit-Learn

## Setup

1. *Clone the repository:*
   bash
   git clone <repository_url>
   cd <repository_directory>
    
2. *Install the required packages:*
    bash
    pip install opencv-python-headless numpy tensorflow keras scikit-image tqdm scikit-learn
    
3. *Provide path files to the images*


## Summary
This code offers a thorough methodology for training a U-Net model for image super-resolution. It incorporates all requisite steps, including data loading, preprocessing, model training, and evaluation. By adhering to the prescribed instructions, users can train the model on their dataset and assess its performance using the Peak Signal-to-Noise Ratio (PSNR) metric.
