# hybrid_quantum-classical-quantum_cnn

This repository implements a **hybrid quantum-classical-quantum convolutional neural network (QCQ-CNN)** architecture for small-sample image classification, combining quantum feature extraction, classical CNN, and optional quantum classification.

## 🧠 Overview

QCQ-CNN is composed of three main stages:

1. **Quantum Feature Extraction**  
   Uses randomly parameterized quantum circuits (Quanvolutional Layer) to transform 2D image patches into quantum-enhanced multi-channel features.

2. **Classical Convolutional Layers**  
   Applies standard 2D convolutions and pooling layers to process the quantum features.

3. **Quantum Classifier (Optional)**  
   Uses a Qiskit-based EstimatorQNN integrated via TorchConnector for end-to-end hybrid learning.

## 📂 Structure


## 🧪 Dataset

- Source: MNIST handwritten digit dataset
- Binary classification with two selected digits (e.g., `[3, 5]`)
- Training set: 50 samples/class
- Test set: 15 samples/class
- Input size: `28x28`, quantum output size: `14x14x4`

## ⚙️ Requirements

bash
pip install pennylane qiskit tensorflow torch torchvision matplotlib seaborn.

## 🚀 Quick Start
Step 1: Extract Quantum Features

## Step 2: Train MLP and Quanvo + MLP

## Step 3: Train Classical CNN and QCCNN

## Step 4: Train QCQ-CNN

## 📚 Acknowledgements
Inspired by PennyLane Quanvolution tutorials and Qiskit QNN examples

Suitable for NISQ experiments and hybrid quantum machine learning research
