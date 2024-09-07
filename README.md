# Neural Networks Projects

## Problem Statement

This project consists of solving two distinct industry-related challenges using neural networks:

### Part I: Signal Quality Prediction (Regression)
A communication equipment manufacturing company wants to build a machine learning model that predicts the quality of signals emitted by their equipment based on various parameters. The project involves creating a regressor model to predict signal quality.

#### **Objective**:
The goal is to build a regression model using neural networks that predicts signal quality based on the available parameters from the equipment.

#### **Data Description**:
The dataset contains several parameters related to signal tests, which are used to predict the final signal quality.

- **Parameters**: Measurable signal characteristics
- **Signal Quality**: The strength or quality of the signal (target variable)

### Part II: Image Classification (Digit Recognition)
Recognizing multi-digit numbers in street-level photographs is an essential component of modern-day mapmaking, such as in Google's Street View. In this project, you will build a neural network image classifier to identify digits from the Street View House Numbers (SVHN) dataset.

#### **Objective**:
The aim is to build a neural network classifier that can recognize numbers from street-level photographs.

#### **Data Description**:
The SVHN dataset contains images of digits obtained from house numbers in Google Street View images. The dataset presents a challenging task as the images may contain various distractors, making the recognition more complex than standard datasets like MNIST.

- **Labels**: Prominent numbers in the images
- **Data Format**: Images are provided in h5py file format, containing centered digits with possible distractors.

## Project Objectives

### Part I: Regression Task (Signal Quality Prediction)
- **Data Import**: Load the dataset containing signal parameters and signal quality.
- **Data Analysis and Visualization**:
  - Perform statistical analysis of the dataset.
  - Conduct univariate, bivariate, and multivariate analysis to uncover hidden patterns.
  - Create new features if necessary to improve model performance.
- **Model Design and Training**:
  - Build a neural network regression model to predict signal quality.
  - Experiment with different model architectures, data transformations, and tuning strategies to improve model performance.
- **Model Saving**: Save the trained model using pickling for future use.

### Part II: Image Classification (Digit Recognition)
- **Data Import**: Load the SVHN dataset.
- **Data Pre-processing and Visualization**:
  - Pre-process and visualize the images from the dataset.
- **Model Design and Training**:
  - Design a neural network image classifier to recognize digits.
  - Experiment with hyperparameter tuning and model refinements to achieve the best accuracy.
- **Performance Evaluation**:
  - Plot training/validation loss and accuracy across epochs.
  - Provide observations and insights based on the model's performance.


