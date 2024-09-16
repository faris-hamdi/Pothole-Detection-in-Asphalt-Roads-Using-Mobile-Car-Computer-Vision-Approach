# Methodology

This document describes the methodology used for the computer vision part of the research.

## Dataset Preparation

The dataset was prepared by collecting images of road surfaces in various conditions. The images were preprocessed through resizing, normalization, augmentation, and labeling.

## Model Selection

Four different convolutional neural network (CNN) architectures were selected for evaluation:
- **AlexNet**: Chosen for its simplicity and proven effectiveness in image classification tasks.
- **ResNet-50**: Used to leverage residual learning for deeper network training.
- **GoogLeNet**: Utilized for its multi-scale feature extraction capabilities.
- **VGG19Net**: Selected for its depth and hierarchical feature learning.

## Training and Evaluation

- The models were trained on the preprocessed dataset using a supervised learning approach.
- Various evaluation metrics were used to assess the models, including accuracy, sensitivity, specificity, positive predictive value, negative predictive value, and F-score.

## Results

The results of the experiments indicated that AlexNet achieved the highest performance, making it a suitable candidate for real-world pothole detection applications.
