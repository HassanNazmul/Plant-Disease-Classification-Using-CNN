# Plant Disease Detection Using Convolutional Neural Networks

## Project Overview

This project aims to develop a Convolutional Neural Network (CNN) model to detect plant diseases from images. The dataset used is the PlantVillage dataset, which contains images of healthy and diseased plant leaves. The project involves the following steps:

1. **Data Loading and Preprocessing**: Load the dataset, resize, and rescale the images.
2. **Model Architecture**: Build a CNN model using TensorFlow's Sequential API.
3. **Model Training**: Train the model on the training dataset and validate it on the validation dataset.
4. **Model Evaluation**: Evaluate the model's performance on the test dataset.
5. **Visualization**: Plot the training and validation accuracy and loss over epochs.
6. **Predictions**: Make predictions on the test dataset and visualize the results.
7. **Model Saving**: Save the trained model for future use.

## Dataset

The dataset used in this project is the PlantVillage dataset. It contains images of healthy and diseased plant leaves. The images are categorized into different classes based on the type of disease.

## Project Steps

### 1. Data Loading and Preprocessing

- Load the dataset from the directory.
- Resize the images to a fixed size.
- Rescale the pixel values to the range [0, 1].

### 2. Model Architecture

- Build a CNN model using TensorFlow's Sequential API.
- The model consists of multiple convolutional layers followed by max-pooling layers.
- Flatten the output and add dense layers for classification.

### 3. Model Training

- Compile the model with an optimizer, loss function, and evaluation metrics.
- Train the model on the training dataset.
- Validate the model on the validation dataset.

### 4. Model Evaluation

- Evaluate the model's performance on the test dataset.
- Print the evaluation metrics.

### 5. Visualization

- Plot the training and validation accuracy over epochs.
- Plot the training and validation loss over epochs.

### 6. Predictions

- Make predictions on the test dataset.
- Visualize the results with actual and predicted labels along with confidence scores.

### 7. Model Saving

- Save the trained model for future use.
