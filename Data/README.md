# Pothole Detection Dataset

This directory contains information about the dataset used for training and evaluating the models in the research.

## Dataset Description

The Pothole Detection Dataset consists of images that depict various road conditions, including:
- **Potholes**: Images showing different types and severities of potholes.
- **Normal Roads**: Images of road surfaces without any visible damage.

### Dataset Preprocessing

1. **Image Resizing**: All images were resized to a standard dimension.
2. **Normalization**: Pixel values were normalized to a range between 0 and 1.
3. **Data Augmentation**: Techniques such as rotation, flipping, and brightness adjustment were applied to enhance model generalization.
4. **Labeling**: Images were labeled to indicate the presence or absence of potholes.
5. **Splitting**: The dataset was divided into training and testing sets to evaluate model performance.

### Accessing the Dataset

The Dataset can be found in: [Pothole Detection Dataset](https://www.kaggle.com/datasets/atulyakumar98/pothole-detection-dataset)