# Plant Disease Identification via Leaf Image Processing

## Overview

This project implements a Convolutional Neural Network (CNN) model for automated plant disease identification using leaf images. The model is trained on the PlantVillage dataset and can classify plant diseases from leaf photographs, helping in early disease detection and crop management.

## Features

* Leaf image preprocessing and normalization
* CNN-based disease classification
* Training and validation using TensorFlow/Keras
* Accuracy and loss visualization
* Disease prediction with confidence score
* Automated end-to-end pipeline

## Dataset

Dataset used: PlantVillage Dataset

The dataset is automatically downloaded from:

https://github.com/spMohanty/PlantVillage-Dataset

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

## Model Architecture

The CNN model consists of:

* Conv2D (32 filters) + MaxPooling
* Conv2D (64 filters) + MaxPooling
* Conv2D (128 filters) + MaxPooling
* Flatten Layer
* Dense Layer (128 neurons)
* Softmax Output Layer

## Training

* Image Size: 128 × 128
* Batch Size: 32
* Validation Split: 20%
* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Epochs: 5

## Results

The model is trained to classify plant diseases from leaf images and provides:

* Predicted disease class
* Confidence score
* Training accuracy
* Validation accuracy

## Future Improvements

* Increase training epochs
* Apply data augmentation
* Use transfer learning (ResNet, MobileNet, EfficientNet)
* Deploy as a web application
* Real-time disease detection using camera input

## Author

Aditya
Electronics Engineering Student | Data Science Enthusiast
