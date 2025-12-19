# Explainable Deepfake Detection using Frame-Based CNN

This repository contains the implementation of a frame-based deepfake detection
pipeline using Convolutional Neural Networks (CNNs) along with explainable AI
techniques such as Grad-CAM and PCA.

The project was developed as part of a Minor Project for the Master of Computer
Applications (MCA) program.

## Project Overview
- Extraction of facial frames from video data
- CNN-based classification of real vs fake faces
- Grad-CAM for visual explainability of model predictions
- PCA-based analysis of feature and gradient representations

## Repository Structure
- notebooks/ : Google Colab notebooks for implementation
- dataset/ : Dataset structure (data not included)
- models/ : Trained CNN models
- requirements.txt : Python dependencies

## Dataset
The Celeb-DFv2 dataset was used for training and evaluation.
Due to size and licensing constraints, the dataset is not included in this repository.

## How to Run
All notebooks were developed and executed using Google Colab.
Upload the notebooks to Google Colab and run the cells sequentially.

## Explainability
Grad-CAM is used to highlight salient facial regions influencing CNN predictions,
while PCA is applied to analyze feature and gradient distributions.
