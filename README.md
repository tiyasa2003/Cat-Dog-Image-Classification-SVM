🐱🐶 Cat vs Dog Image Classification using SVM

This project implements a Support Vector Machine (SVM) to classify images of cats and dogs from the Kaggle dataset.
It includes data preprocessing, feature extraction, model training, and evaluation, providing insights into model performance and accuracy.

Overview

The goal of this project is to classify images of cats and dogs using a Support Vector Machine (SVM).
SVM is a supervised machine learning algorithm that works well for binary classification tasks like this.

Dataset

We are using the Cats and Dogs dataset from Kaggle:
🔗 Kaggle Dataset Link

The dataset contains two classes:

Cats

Dogs

Tech Stack

Python

NumPy, Pandas (data handling)

OpenCV / PIL (image preprocessing)

Scikit-Learn (SVM classifier)

Matplotlib, Seaborn (visualization)

Project Workflow

1. Data Preprocessing

Load and resize images

Convert images to grayscale or extract features

Flatten images for SVM input

2. Feature Extraction

Normalize pixel values

Optional: Extract histogram of oriented gradients (HOG) features

3. Model Training

Split data into training and test sets

Train an SVM classifier on the training data

Evaluate model using accuracy, confusion matrix, and classification report

4. Prediction

Predict class (cat or dog) for unseen images

Results

Provides high accuracy in distinguishing cats and dogs

Visualization of correctly and incorrectly classified images

Confusion matrix and classification report for performance evaluation

How to Run
# Clone the repository
git clone https://github.com/your-username/Cat-Dog-Image-Classification-SVM.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook CatDogSVM.ipynb

About

A machine learning project demonstrating SVM-based image classification for cats and dogs. Useful for learning image preprocessing, feature extraction, and SVM model application in computer vision tasks.
