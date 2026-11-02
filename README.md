# Multiple Sclerosis Lesion Segmentation Using ResU-Net

## Overview

This project explores the use of a Residual U-Net (ResU-Net) deep learning architecture to automatically segment multiple sclerosis (MS) lesions in brain MRI images.

## Dataset

The project uses the [MSSEG 2016 dataset](https://www.kaggle.com/datasets/sasikumarg/multiple-sclerosis-2016), which includes multi-sequence MRI scans and consensus lesion segmentation masks.

## Methodology

- Load and preprocess MRI images and segmentation masks.
- Prepare input images and ground-truth labels.
- Train a ResU-Net model using TensorFlow and Keras.
- Evaluate performance using Dice coefficient, accuracy, and loss.
- Visualize predicted lesion masks.

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- NiBabel
- OpenCV
- Matplotlib
- scikit-learn

## Evaluation

Training curves and segmentation results will be added after model training and evaluation are completed.

## Limitations

The dataset size and patient-level data splitting may affect model generalization. This project is for educational and research purposes and is not intended for clinical diagnosis.
