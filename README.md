# 🌿 Natural Image Classification

This project builds and trains Convolutional Neural Networks (CNNs) to classify natural images into six categories:

> **buildings**, **forest**, **glacier**, **mountain**, **sea**, and **street**

It explores and compares multiple popular architectures, including **VGG16**, **ResNet**, and a custom-built **AlexNet-style** model.

---

## 🔧 Key Features

- Image preprocessing: resizing, normalization, and augmentation  
- Implemented and trained three different models:
  - ✅ **VGG16** (Transfer Learning)
  - ✅ **ResNet** (Deep Residual Learning)
  - ✅ **AlexNet-inspired** custom CNN
- Training optimization with:
  - `EarlyStopping`
  - `ModelCheckpoint`
- Evaluation with:
  - Accuracy/loss plots
  - Confusion matrix
  - Prediction visualizations

---

## 📁 Dataset

- Natural scene image dataset with labeled folders for each class
- Loaded using **Keras `ImageDataGenerator`**
- Automatically split into:
  - **Training set**
  - **Validation set**
  - **Test set**

---

## 📊 Results

- All three models were trained and evaluated on the same dataset
- Performance compared on unseen test images
- Visual outputs include:
  - Training vs. validation accuracy/loss plots
  - Confusion matrix
  - Sample predictions with confidence scores

---

## 📌 How to Use

1. Clone the repo and install dependencies:
   ```bash
   git clone https://github.com/your-username/natural-image-classification.git
   cd natural-image-classification
   
