## Cat and Dog Classification
This project aims to build a Convolutional Neural Network (CNN) model to classify images of cats and dogs using a dataset from Kaggle. The goal is to achieve high accuracy and export the trained model in multiple formats for broader usability.

## Dataset
The dataset is sourced from Kaggle and is pre-split into training, validation, and test sets. It consists of labeled images of cats and dogs, allowing the model to learn distinguishing features for accurate classification.

## Model Architecture
The model is built using a CNN with the following key layers:

Conv2D: Extracts features from images using convolutional filters.
MaxPooling2D: Reduces spatial dimensions while preserving important features.
Dense (Fully Connected Layers): Learns complex patterns for final classification.
Optimizer: Adam optimizer is used to improve learning efficiency.

## Output
- The model achieves an accuracy of 85% or higher on both training and testing data.
- The trained model is saved in multiple formats for different use cases:
  - SavedModel (TensorFlow format)
  - TFJS (TensorFlow.js for web deployment)
  - TFLite (TensorFlow Lite for mobile and edge devices)
    
## Installation
To set up the environment and install dependencies, run the following command:

!pip install tensorflow numpy matplotlib tensorflowjs

This project demonstrates how deep learning can effectively classify images of cats and dogs, making it a great introduction to CNN-based image classification.







