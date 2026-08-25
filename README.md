# cognitive-workload-assessment

# Cognitive Workload Assessment Using Deep Learning

A machine learning and deep learning project for **cognitive workload classification using EEG signals**.

## Overview

This project uses the **STEW (Simultaneous Task EEG Workload) dataset** to analyze EEG signals and classify cognitive workload into **low, medium, and high** levels.

The project involves:

* EEG signal preprocessing
* Feature extraction
* Traditional machine learning
* Deep learning
* Model comparison and evaluation

## Models Used

### Machine Learning

* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest

### Deep Learning

* 1D Convolutional Neural Network (1D-CNN)
* Bidirectional LSTM (Bi-LSTM)

## Pipeline

```text
EEG Data
   ↓
Preprocessing
   ↓
Feature Extraction
   ↓
ML / Deep Learning Models
   ↓
Workload Classification
   ↓
Performance Evaluation
```

## Dataset

The project uses the **STEW EEG dataset**, containing EEG recordings collected using a 14-channel setup at a sampling rate of 128 Hz.

## Results

The evaluated models achieved the following accuracies:

| Model         |   Accuracy |
| ------------- | ---------: |
| KNN           |     77.34% |
| SVM           |     69.97% |
| Decision Tree |     78.56% |
| Random Forest |     88.44% |
| 1D-CNN        | **89.79%** |
| Bi-LSTM       |     88.14% |

## Objective

The objective of this project is to explore the use of machine learning and deep learning techniques for **objective cognitive workload assessment from EEG signals**.

