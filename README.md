# Semantic Segmentation Project

This project focuses on semantic segmentation of medical images, specifically targeting skin lesions such as melanoma and moles. The goal is to accurately segment these lesions from the images using deep learning techniques.

## Project Structure

- **semantic_segmentation.ipynb**: This notebook contains the initial setup and data preprocessing steps for the project.
- **unet_segnet_segmentation.ipynb**: This notebook includes the implementation of U-Net and SegNet models for semantic segmentation.

## Data

The dataset used in this project is from the [ADDI project](https://www.fc.up.pt/addi/ph2%20database.html). It contains images of skin lesions, which are categorized into two types: melanoma and moles.

## Steps

1. **Data Download**: Download the dataset from the provided link.
2. **Data Preprocessing**: Preprocess the images and masks to prepare them for training.
3. **Model Implementation**: Implement U-Net and SegNet models for segmentation.
4. **Training and Evaluation**: Train the models on the dataset and evaluate their performance.

## Requirements

- Python 3.7+
- PyTorch
- OpenCV
- scikit-image
- NumPy
- Matplotlib
- scikit-learn
