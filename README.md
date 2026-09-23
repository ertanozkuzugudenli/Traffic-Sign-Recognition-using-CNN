# Traffic Sign Recognition using CNN

This repository contains the source code for a Convolutional Neural Network (CNN) model designed to automatically classify traffic sign images into 28 distinct categories. The project was developed using **Python**, **TensorFlow**, and **Keras** within the Google Colab environment.

## Project Overview
Accurate traffic sign recognition is a fundamental component of Autonomous Driving Systems and Advanced Driver-Assistance Systems (ADAS). This project demonstrates an end-to-end deep learning pipeline, from loading and preprocessing image data stored on Google Drive, to training a custom neural network and rigorously evaluating its predictive performance.

## Key Features
*   **Custom CNN Architecture:** Designed and trained a Convolutional Neural Network from scratch using TensorFlow and Keras to extract complex image features.
*   **28-Class Classification:** The model is trained to distinguish between 28 different traffic sign categories.
*   **Cloud-Based Training Pipeline:** Utilized Google Colab for GPU-accelerated training, effectively handling the dataset directly via Google Drive integration.
*   **Comprehensive Evaluation:** Model performance is validated using advanced metrics beyond simple accuracy. The evaluation includes a detailed **Classification Report** (Precision, Recall, F1-Score) and a visualized **Confusion Matrix** to analyze class-specific predictions and misclassifications.

## Technologies & Libraries Used
*   **Language:** Python
*   **Deep Learning Framework:** TensorFlow, Keras
*   **Environment:** Google Colab
*   **Data Processing & Evaluation:** NumPy, Pandas, Scikit-Learn
*   **Data Visualization:** Matplotlib, Seaborn

## Repository Contents
*   `Traffic_Sign_Recognition.ipynb` (or `.py`): The main notebook/script containing data preprocessing, model architecture, training loop, and evaluation metrics.
