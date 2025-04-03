# fakevsreal-face-detection
# Fake vs Real Image Classification

A deep learning model that classifies human face images as real or fake using a Convolutional Neural Network (CNN).

## Features
- Preprocesses and balances image data
- Trains a CNN model for classification
- Evaluates performance with accuracy and confusion matrix
- Predicts real or fake labels for new images

## Usage
1. Upload dataset and extract images
2. Train the model with `train.py`
3. Evaluate results and visualize accuracy
4. Predict on new images using `predict.py`

## Model Architecture
- CNN with multiple convolutional & pooling layers
- Regularization with dropout and L2
- Adam optimizer, binary cross-entropy loss

## Results
- Displays accuracy and classification report
- Saves model as `fakevsreal.h5` for later use


