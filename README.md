# Image Classification Using Hand-Crafted Features, Neural Networks, and CNNs

This project compares three image classification methods: hand-crafted features + SVM, simple neural networks, and convolutional neural networks (CNNs) on the TinyImageNet100 dataset (15 selected classes). It was developed as part of the ECS8053 – Computer Vision coursework.

## 📊 Methods Implemented

### 1. Hand-Crafted Features + SVM
- ORB + Bag of Words
- SIFT + Bag of Words
- ORB + Fisher Vector
- SIFT + Fisher Vector

### 2. Neural Networks
- Fully connected layers with ReLU, batch normalization, and dropout.

### 3. Convolutional Neural Networks (CNNs)
- Baseline CNN with grayscale input
- Advanced CNN with data augmentation and color input

## 🧪 Results Summary

| Method               | Accuracy (%) |
|----------------------|--------------|
| ORB + BoW            | 7.8          |
| SIFT + BoW           | 25.0         |
| ORB + Fisher Vector  | 7.0          |
| SIFT + Fisher Vector | 25.0         |
| Neural Network       | 24.0         |
| CNN (Advanced)       | **64.9**     |

## 📁 Directory Structure

- `handcrafted_features/`: Traditional computer vision pipelines with ORB and SIFT.
- `neural_network/`: Code for simple MLP-based image classification.
- `cnn/`: PyTorch-based CNN implementations.
- `utils/`: Scripts for dataset preparation and visualization.

## ⚙️ Setup Instructions

```bash
git clone https://github.com/maheshnilewar/image-classification-project.git
cd image-classification-project
pip install -r requirements.txt
