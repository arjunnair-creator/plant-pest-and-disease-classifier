# Plant Pest and Disease Detection

This repository contains a deep learning solution for identifying pests and diseases in agricultural crops. The project utilizes a Keras-based classification model to analyze image data and provide real-time diagnostic results.

## 🌟 Overview

The `Pest (1).ipynb` notebook provides a complete inference pipeline that allows users to:
- Load a pre-trained Convolutional Neural Network (CNN) model.
- Upload images of affected plants directly within a Colab/Jupyter environment.
- Preprocess images for optimal model prediction (224x224 resolution).
- Categorize plant health into specific pest or disease classes.

## 🛠️ Requirements

- Python 3.8+
- TensorFlow 2.12.1
- Keras
- NumPy
- Pillow (PIL)
- Matplotlib

## 🚀 Getting Started

### 1. Installation
Ensure you have the necessary libraries installed. You can install the specific version of TensorFlow used in this project via:
```bash
pip install tensorflow==2.12.1 numpy pillow matplotlib
