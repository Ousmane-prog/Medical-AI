# Medical AI – Cardiomegaly Detection from Chest X-rays

This project implements a deep learning pipeline using TensorFlow to detect **cardiomegaly** (enlarged heart) from chest radiography images. The goal is to automate image classification for medical diagnosis support.

## Project Overview

- **Dataset**: Chest X-ray images labeled as "Cardiomegaly" or "No Finding"
- **Model**: Transfer learning using **InceptionV3**
- **Framework**: TensorFlow / Keras
- **Output**: Binary classification (Cardiomegaly vs. Normal)

## Features

- Data preprocessing (resizing, normalization)
- Data augmentation (rotation, zoom, shift, shear)
- Balanced sampling between positive/negative cases
- Transfer learning with a frozen convolutional base
- Model training, evaluation, and performance visualization
- Prediction function for new images
- Results exported to a CSV with confidence scores

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, PIL
  
## Preview
<img width="1431" height="735" alt="image" src="https://github.com/user-attachments/assets/b927f045-bc4f-4746-b80d-4fef85aa6d16" />
