# BreastHistCNN (BH-CNN)

## Project Overview

This project explores breast histopathology image classification using the BreaKHis dataset, comparing three deep learning approaches:

- A lightweight Shallow Convolutional Neural Network (CNN)
- A pretrained Swin Transformer (Swin-T)
- A Multi-task CNN for binary and histological subtype classification

## Dataset and Methodology

The audited dataset contains 7,784 images from 81 patients. Patient-level splitting was used to reduce data leakage between training, validation, and testing.

## Model Evaluation

The models were evaluated using ROC-AUC, sensitivity, specificity, F1-score, and other classification metrics.

## Implementation

The complete Jupyter notebook containing the Python implementation, preprocessing pipeline, model architectures, and evaluation methodology is available in this repository.

The BreaKHis dataset and trained model checkpoints are not included. Reproducing the evaluation requires obtaining these files separately and configuring the execution environment.

An executed HTML version of the notebook, including experimental results and visualizations, is provided separately for academic review.

## Research Status

Academic research project. The models are experimental and are not intended for clinical diagnosis.
