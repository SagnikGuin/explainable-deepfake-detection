# Explainable Deepfake Detection using Frame-Based CNN

This repository contains the implementation of a frame-based deepfake detection
pipeline using Convolutional Neural Networks (CNNs) and explainable AI techniques
such as Grad-CAM and PCA.

The project was developed as part of a Minor Project for the Master of Computer
Applications (MCA).

## Project Overview
- Face extraction from video frames
- CNN-based real vs fake classification
- Grad-CAM visualization for explainability
- PCA-based analysis of features and gradients

## Repository Structure
- notebooks/ : Google Colab notebooks
- dataset/ : Dataset structure (data not included)
- models/ : Trained models
- requirements.txt : Python dependencies

## Dataset
The Celeb-DFv2 dataset was used for experimentation.
Due to size and licensing restrictions, the dataset is not included.

## How to Run
Upload the notebooks to Google Colab and execute the cells sequentially.

## Explainability
Grad-CAM and PCA are used to interpret CNN predictions and highlight manipulated
facial regions in deepfake videos.
