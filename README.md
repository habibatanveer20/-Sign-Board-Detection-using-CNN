# Sign Board Detection using CNN

## Overview
This project is based on a Convolutional Neural Network (CNN) model that detects and classifies sign boards.  
The model was trained using a labeled dataset obtained from Kaggle. Preprocessing steps were applied to improve accuracy.

## Dataset
Source: Kaggle  
The dataset was imported into Google Colab from Google Drive.  

## Tools and Libraries
- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

## Steps Performed
1. Imported the dataset from Google Drive.
2. Resized and normalized the images.
3. Designed a CNN model with multiple Conv2D and MaxPooling layers.
4. Trained the model and evaluated its accuracy.
5. Saved the trained model in .h5 format.
6. Saved the class mapping in a .json file for future use.

## Model Performance
- Training Accuracy: 99%
- Validation Accuracy: 98%  
(Update these values with your actual results if needed)

## Saved Files
- my_model.h5 → Trained CNN model
- classes.json → Class index mapping
- X_train.npy, y_train.npy → Preprocessed training data
- X_test.npy, y_test.npy → Preprocessed testing data

## How to Use
1. Mount Google Drive in Colab:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
