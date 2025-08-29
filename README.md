# Fashion MNIST Image Classification

A comprehensive deep learning project that implements and compares multiple machine learning algorithms for classifying images from the Fashion MNIST dataset.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00)

## 📁 Dataset

The project uses the **[Fashion MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist)** dataset from Kaggle, containing 70,000 grayscale images across 10 clothing categories:
- T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

## 🚀 Features

- **Data Exploration & Visualization**: Comprehensive EDA with class distribution analysis
- **Multiple Algorithm Implementation**:
  - Traditional ML: Logistic Regression, Random Forest, SVM
  - Deep Learning: Convolutional Neural Network (CNN)
- **Comparative Analysis**: Performance comparison across different algorithms
- **Detailed Evaluation**: Classification reports, confusion matrices, and ROC curves

## 🛠️ Technologies Used

- **Google Colab** - Cloud-based Jupyter notebook environment
- **Python 3.8+**, **TensorFlow/Keras**, **scikit-learn**
- **NumPy & Pandas** for data manipulation
- **Matplotlib & Seaborn** for data visualization

## 📊 Model Performance

| Model | Test Accuracy |
|-------|---------------|
| **CNN (Deep Learning)** | ~92% |
| **Support Vector Machine** | ~89% |
| **Random Forest** | ~87% |
| **Logistic Regression** | ~84% |

## ⚡ Quick Start

### Option 1: Google Colab (Recommended)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WoADppeDStlomTGsg5LshzD7WAb6beV3?usp=sharing)

Click the button above to open and run the notebook directly in Google Colab. No installation required!

### Option 2: Local Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/Plasmaa/Deep-Learning---Fashion-MNIST.git
   cd Deep-Learning---Fashion-MNIST
