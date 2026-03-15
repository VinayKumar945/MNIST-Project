MNIST Handwritten Digit Classification

A machine learning project that builds and evaluates models to classify handwritten digits using the famous MNIST dataset. The project demonstrates a full machine learning workflow including data preprocessing, model training, evaluation, and prediction.

Project Overview

Handwritten digit recognition is a classic problem in computer vision and machine learning. The MNIST dataset contains thousands of labeled images of digits (0–9), each represented as a grayscale image.

In this project, we train a machine learning model to accurately recognize and classify these digits.

This project showcases practical skills in:

Data preprocessing

Feature scaling

Model training

Performance evaluation

Prediction on unseen data

Dataset

The project uses the MNIST dataset, which contains:

70,000 images of handwritten digits

28 × 28 grayscale images

10 classes (digits 0–9)

Dataset split:

60,000 training images

10,000 testing images

Each image is flattened into a feature vector of 784 pixels.

Tech Stack

This project uses the following tools and libraries:

Python

NumPy

Pandas

Matplotlib

Scikit-learn

Jupyter Notebook

Machine Learning Workflow

The notebook follows a structured ML pipeline:

1. Data Loading

The MNIST dataset is loaded and explored to understand its structure and distribution.

2. Data Preprocessing

Reshaping image data

Normalizing pixel values

Preparing training and test sets

3. Model Training

A classification model is trained on the dataset to learn patterns from handwritten digits.

4. Model Evaluation

The model is evaluated using metrics such as:

Accuracy

Confusion Matrix

Classification Report

5. Predictions

The trained model is used to predict digits on unseen test images.

Results

The trained model successfully learns patterns in handwritten digits and achieves strong classification performance on the test dataset.

The notebook also visualizes predictions and evaluates model performance to better understand where the model performs well and where errors occur.