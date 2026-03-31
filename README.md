# deeplense-gsoc-2026
DeepLense GSoC 2026 submission: Multi-class classification and gravitational lens finding using CNNs (PyTorch)

# DeepLense GSoC 2026 Submission

## Overview
This repository contains my solutions for the DeepLense GSoC 2026 evaluation tests.

## Test I: Multi-Class Classification
Implemented a Convolutional Neural Network (CNN) to classify gravitational lensing images into three classes using PyTorch. The dataset was processed from .npy format and evaluated using ROC curve and AUC score.

## Test V: Gravitational Lens Finding
Developed a binary classification model to identify strong gravitational lenses from non-lensed images. The model addresses class imbalance using weighted loss and is evaluated using ROC-AUC.

## Implementation Details
- Framework: PyTorch
- Data format: NumPy (.npy)
- Model: CNN with adaptive pooling
- Evaluation: ROC Curve and AUC Score

## Repository Structure
- test1_multiclass_classification.ipynb: Solution for Test I
- test5_lens_finding.ipynb: Solution for Test V

## Author
Vignathi Bhairavabhotla
