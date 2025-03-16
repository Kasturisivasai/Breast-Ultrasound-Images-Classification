Breast Ultrasound Image Classification Project
This is a complete Jupyter notebook project focused on classifying breast ultrasound images using PyTorch and Torchvision. Here's an overview of what the project covers:
1. Project Overview
This project builds a deep learning model to classify breast ultrasound images into three categories:

Normal (healthy tissue)
Benign (non-cancerous lesions)
Malignant (cancerous lesions)

2. Key Components
Dataset Analysis & Preparation

The Kaggle dataset includes 780 breast ultrasound images from 600 female patients
Images are organized by classification (normal, benign, malignant)
The notebook includes code to download the dataset or work with data you've already downloaded

Model Architecture

Transfer learning using ResNet-18 pretrained on ImageNet
Custom classification head for the three breast tissue categories
Data augmentation techniques specifically useful for medical imaging

Training & Evaluation

Complete training pipeline with validation
Medical-specific metrics including:

Sensitivity/specificity analysis
ROC curves and AUC for each class
Confusion matrix visualization
