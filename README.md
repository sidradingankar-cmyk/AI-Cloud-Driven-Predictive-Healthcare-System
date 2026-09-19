# Cloud-Driven Predictive Healthcare System

## Project Overview

This project is an implementation component of a proposed Cloud-Driven Predictive Healthcare System for disease prediction using medical imaging and patient health information.

The research system combines deep learning techniques for analyzing chest X-ray images and sequential patient health records. The proposed architecture uses Convolutional Neural Networks (CNN), HierbaNetV1, and Long Short-Term Memory (LSTM) networks.

For this implementation, the focus is on developing and evaluating the CNN-based chest X-ray classification component.

## Objectives

The main objectives of this project are:

- Process and classify chest X-ray images using deep learning.
- Develop a CNN model for binary chest X-ray classification.
- Preprocess medical images into a suitable format for model training.
- Train and evaluate the CNN model using accuracy and classification metrics.
- Demonstrate how the CNN component can form part of a larger cloud-based healthcare prediction system.
- Provide a foundation for future integration with temporal patient-record analysis using LSTM.

## Research System

The proposed research system consists of several major components:

1. Chest X-ray image preprocessing
2. CNN-based spatial feature extraction
3. HierbaNetV1 for multi-scale feature extraction and attention
4. LSTM-based temporal patient-record analysis
5. Feature fusion
6. Disease prediction
7. Confidence/risk estimation
8. Cloud-based storage and dashboard visualization

The complete research architecture is broader than the prototype implemented in this repository.

## Implementation Scope

This repository implements the CNN component of the proposed system.

The implemented model performs binary classification of chest X-ray images into:

- NORMAL
- PNEUMONIA

The implementation was developed using Google Colab and TensorFlow/Keras.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Pillow
- Google Colab
- Kaggle dataset

## Dataset

The implementation uses the Chest X-Ray Pneumonia dataset available through Kaggle.

The dataset contains chest X-ray images organized into NORMAL and PNEUMONIA classes.

The images are resized to:

```text
224 × 224 pixels
