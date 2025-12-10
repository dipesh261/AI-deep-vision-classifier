# AI-deep-vision-classifier
AI-deep-vision-classifie is a deep learning project showcasing the implementation, training, and evaluation of Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN).
The project demonstrates image classification using CNNs and general prediction/classification tasks using ANNs, with clean modular code and an easy-to-understand structure for learning and experimentation

# ann-cnn-model-suite

A deep learning project featuring both Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN).  
This repository provides a clean, modular implementation of neural network models for tasks such as image classification and general prediction.

---

## 🚀 Project Overview

This project demonstrates:

### ✔️ ANN (Artificial Neural Network)
- Works for **tabular data**, regression, and classification
- Fully-connected layers
- Customizable architecture

### ✔️ CNN (Convolutional Neural Network)
- Designed for **image classification**
- Includes convolution, pooling, and dense layers
- Works with datasets like MNIST, CIFAR-10, Custom images

---

## 📁 Project Structure

ann-cnn-model-suite/
│
├── data/ # Datasets (images or CSV)
├── models/ # Saved .h5 or .pt models
├── notebooks/ # Jupyter notebooks for training/testing
├── src/
│ ├── ann_model.py # ANN architecture
│ ├── cnn_model.py # CNN architecture
│ ├── train_ann.py # Training script for ANN
│ ├── train_cnn.py # Training script for CNN
│ ├── evaluate.py # Model evaluation utilities
│ └── utils.py # Helper functions
│
├── requirements.txt
└── README.md
---

## 🛠 Installation

```bash
git clone https://github.com/yourusername/ann-cnn-model-suite.git
cd ann-cnn-model-suite
pip install -r requirements.txt

python src/train_ann.py

python src/train_cnn.py

python src/evaluate.py



