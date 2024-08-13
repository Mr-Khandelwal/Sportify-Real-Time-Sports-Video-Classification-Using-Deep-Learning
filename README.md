
# Sportify-Real-Time-Sports-Video-Classification-Using-Deep-Learning

This project implements a deep learning-based video classification system to recognize and categorize sports activities from video footage. The system leverages transfer learning using the ResNet50 architecture, fine-tuned to classify videos into sports categories such as boxing, swimming, and tennis.Uses deep learning (ResNet50) for sports activity recognition from videos. Includes data preprocessing, augmentation, and real-time deployment with Python, TensorFlow/Keras, and OpenCV. Achieves high accuracy in classifying sports activities

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)

## Overview
The project addresses the challenge of automatically classifying sports activities from video data. By using a pre-trained ResNet50 model, this system can effectively identify different sports in real-time, making it suitable for applications in sports analytics and content management.

## Features
- **Real-time video classification** using a pre-trained ResNet50 model.
- **Data augmentation** to improve model generalization.
- **Support for multiple sports categories** including boxing, swimming, and tennis.
- **Video processing** with OpenCV for frame extraction and resizing.

## Technologies
- **Python**
- **TensorFlow/Keras**
- **OpenCV**
- **scikit-learn**
- **NumPy**

## Dataset
https://drive.google.com/file/d/1AMHdRyj5wtrPdKf57HV4AVPOD36E0M8K/view

## Installation
Step 1:
```
clone git https://github.com/Mr-Khandelwal/Sportify-Real-Time-Sports-Video-Classification-Using-Deep-Learning.git
```
Step 2:
```
virtualenv venv
```
Step 3 :
```
.\venv\Scripts\Activate.ps1
```
Step 4:
```
pip install -r requirments.txt
```

## Usage

### Model Training
To train the model on your dataset:
```bash
run all train_model.ipynb
```
- Ensure your dataset is organized into subfolders for each category.

## Results
The model achieves high accuracy in classifying sports activities, effectively distinguishing between different categories in real-time.
