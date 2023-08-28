# FACE DETECTION
# YOLOv8 Training & Evaluation on Google Colab with Kaggle Dataset

This repository contains code for training and evaluating the YOLOv8 model on a dataset sourced from Kaggle. Below are the detailed steps to run the code and visualize the model's performance.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Setup](#setup)
3. [Model Training](#model-training)
4. [Model Evaluation](#model-evaluation)
5. [Visualization](#visualization)

## Prerequisites

- A Google account to access [Google Colab](https://colab.research.google.com/).
- A Kaggle account for [dataset](https://www.kaggle.com/) download.

## Setup

1. *Google Colab Initialization*:
    - Open Google Colab and create a new Python3 notebook.
    - Set your runtime type to GPU for faster computation through `Runtime > Change runtime type`.

2. *Kaggle Dataset Download*:
         Download your desired dataset from [kaggle]( https://www.kaggle.com/datasets/sbaghbidi/human-faces-object-detection) You can either:
    - Upload it directly to Google Colab using the upload button in the sidebar.
    - Save the dataset to Google Drive and access it from Colab using `drive.mount('/content/drive')`.

## Model Training

1. *Initialize Model*:
    - Insert code here on how you initialize and configure your YOLOv8 model.

2. *Training Phase*:
    - After data preprocessing and augmentation, train the YOLO model using the provided training function.

## Model Evaluation

1. *Validation Metrics*:
    - Use the functions provided to calculate various evaluation metrics on the validation set like mAP, Precision, Recall, etc.

2. *Test Metrics*:
    - Similar to validation, compute the model's performance metrics on the test dataset.

## Visualization

1. *Performance Curves*:
    - Visualize the performance curves such as Loss vs Epochs, Precision-Recall curves, etc., using the defined functions.

2. *Model Predictions*:
    - Display actual vs predicted images to see how well the model is detecting objects in test images.
