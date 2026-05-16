# Handwritten Drug Classification using Deep Learning

## Overview
This project presents an AI-based system for recognizing handwritten drug names from medical prescriptions using Deep Learning techniques. The system helps reduce medication errors caused by unclear handwriting and supports digital healthcare transformation.

The project compares three deep learning models:

- Custom Convolutional Neural Network (CNN)
- EfficientNetB0
- ResNet50

Among all models, ResNet50 achieved the best performance with a test accuracy of **77.44%**.

---

## Features
- Handwritten prescription recognition
- Image preprocessing and enhancement
- Drug name classification
- Transfer Learning implementation
- Model comparison and evaluation
- Streamlit deployment prototype

---

## Dataset
Dataset used:
**Doctor Handwritten Prescription BD Dataset**

The dataset contains handwritten medicine word images collected from real medical prescriptions.

### Dataset Split
- Training Images: 3120
- Validation Images: 780
- Testing Images: 780

Total Images: 4680

---

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Streamlit

---

## Preprocessing Techniques
- Grayscale Conversion
- Otsu Thresholding
- Image Resizing
- Pixel Normalization
- Data Augmentation

---

## Models
### 1. CNN
Custom-built convolutional neural network trained from scratch.

### 2. EfficientNetB0
Transfer learning model pretrained on ImageNet.

### 3. ResNet50
Deep residual transfer learning architecture with the best overall performance.

---

## Results

| Model | Test Accuracy |
|------|------|
| CNN | 63.85% |
| EfficientNetB0 | 69.62% |
| ResNet50 | 77.44% |

