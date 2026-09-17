# Face Mask Detection using CNN and AlexNet

## 📌 Project Overview

This project implements a **Face Mask Detection system using Deep Learning**. The system classifies facial images into two categories:

- **With Mask**
- **Without Mask**

Two Convolutional Neural Network architectures are implemented and compared:

1. Basic CNN
2. AlexNet-inspired CNN

The project evaluates both models using accuracy, precision, recall, F1-score, confusion matrix, training time, and number of parameters.

---

## 🎯 Objectives

- Load and preprocess a real-world face mask image dataset.
- Perform binary classification of masked and unmasked faces.
- Build and train a Basic CNN model.
- Build and train an AlexNet-inspired CNN model.
- Compare the performance of both architectures.
- Evaluate the models using classification metrics and confusion matrices.
- Perform single-image prediction using the trained models.

---

## 📊 Dataset

The project uses the **Face Mask Detection Dataset** available on Kaggle.

**Dataset:**  
https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

### Dataset Details

| Class | Number of Images |
|---|---:|
| With Mask | 3,725 |
| Without Mask | 3,828 |
| **Total** | **7,553** |

The dataset is divided into:

- Training: 6,043 images
- Validation: 1,510 images

The dataset is downloaded automatically using **KaggleHub**, so the dataset files are not included in this repository.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub
- Google Colab

---

## 🧠 Models Used

### 1. Basic CNN

The Basic CNN consists of:

- 3 Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layer
- Dropout
- Sigmoid output layer

**Total Parameters:** 3,304,769

---

### 2. AlexNet

The AlexNet-inspired architecture consists of:

- Multiple convolutional layers
- Large initial convolution filter
- Max Pooling
- Batch Normalization
- Fully connected layers
- Dropout
- Sigmoid output layer

**Total Parameters:** 24,732,417

---

## ⚙️ Data Preprocessing

Images are resized to:

```text
128 × 128 × 3
