# 🧠 Brain Tumor Classification Using Deep Learning & Grad-CAM
## 📌 Project Overview

This project builds a deep learning model for multi-class brain tumor classification using MRI images.
The model is based on transfer learning with EfficientNetB1 and includes Grad-CAM visualization to interpret model predictions.

The system classifies MRI scans into:

* Glioma

* Meningioma

* Pituitary Tumor

* No Tumor

## 🗂 Dataset

The dataset used is the Brain Tumor MRI Dataset from Kaggle:

🔗 Source: Kaggle
Dataset: Brain Tumor MRI Dataset

* 4 Classes

* 1400 training images per class

* 400 testing images per class

## 🛠 Technologies Used

* Python

* TensorFlow / Keras

* OpenCV

* NumPy

* Matplotlib

* Seaborn

* imutils

## 🧠 Model Architecture

The model uses:

* Transfer Learning with EfficientNetB1

* Global Max Pooling

* Dropout (0.5)

* Dense Softmax Layer (4 classes)

## Why EfficientNet?

EfficientNet provides:

* Better accuracy

* Fewer parameters

* Faster training

## ✂️ Image Preprocessing

* Cropping using contour detection (OpenCV)

* Resize to 240x240

## Data Augmentation:

* Rotation

* Height shift

* Horizontal flip

## 🔥 Grad-CAM Visualization

Grad-CAM (Gradient-weighted Class Activation Mapping) is used to:

* Highlight important regions in MRI scans

* Improve model interpretability

* Increase trust in predictions

## 📊 Results

The model achieved excellent performance on the MRI dataset:

Training Accuracy: 99.30%

Testing Accuracy: 94.82%

These results demonstrate strong generalization with minimal overfitting.
