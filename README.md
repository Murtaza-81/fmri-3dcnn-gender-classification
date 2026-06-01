# fmri-3dcnn-gender-classification
3D CNN based gender classification using resting-state fMRI neuroimaging data with PyTorch.

## Overview

This project implements a 3D Convolutional Neural Network (3D-CNN) for gender classification using resting-state functional Magnetic Resonance Imaging (fMRI) brain volumes.

The model was trained on preprocessed resting-state fMRI data and evaluated using standard classification metrics.

## Dataset

* Training Samples: 147
* Testing Samples: 37
* Volume Size: 64 × 64 × 34
* Data Type: float32

Original dataset source:

Li et al. (2021), Dataset of whole-brain resting-state fMRI of 227 young and elderly adults acquired at 3T.

## Methodology

The implemented architecture includes:

* 3D Convolution Layers
* Batch Normalization
* ReLU Activation
* Max Pooling
* Adaptive Average Pooling
* Dropout Regularization
* Fully Connected Layers

## Results

| Metric          | Value  |
| --------------- | ------ |
| Accuracy        | 75.68% |
| Macro Precision | 77.42% |
| Macro Recall    | 76.62% |
| Macro F1-score  | 75.60% |

## Generated Outputs

* Accuracy Curve
* Loss Curve
* Confusion Matrix
* Trained Model
* Evaluation Metrics

## Technologies

* Python
* PyTorch
* NumPy
* Scikit-Learn
* Matplotlib
* Jupyter Notebook

## Future Work

* Transfer Learning
* Attention-based 3D CNN
* Vision Transformers
* Cross Validation
* Larger Neuroimaging Datasets

