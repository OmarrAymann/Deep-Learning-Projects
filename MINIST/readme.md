# 🧠 MNIST Digit Classification with CNN

## 📄 Overview / Abstract

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The MNIST dataset is a benchmark in the field of computer vision and deep learning, and this project demonstrates effective use of deep learning techniques for image classification tasks.

---
## 📊 Dataset Description

The MNIST dataset consists of:

- 60,000 training images  
- 10,000 test images  
- Each image is a 28x28 grayscale image representing digits from 0 to 9  
- The labels are integers from 0 to 9

Dataset is loaded directly from `tensorflow.keras.datasets`.

---

## 🧱 Model Architecture

The CNN model used in this project includes:

- **Input Layer**: (28, 28, 1)
- **Conv2D Layer**: 32 filters, (3x3), ReLU
- **MaxPooling2D**: (2x2)
- **Conv2D Layer**: 64 filters, (3x3), ReLU
- **MaxPooling2D**: (2x2)
- **Flatten Layer**
- **Dense Layer**: 64 units, ReLU
- **Output Layer**: 10 units (softmax activation for classification)

The model uses the `sparse_categorical_crossentropy` loss function and the `adam` optimizer.

---

## 🏋️ Training Details

- **Epochs**: 5  
- **Batch size**: 64  
- **Optimizer**: Adam  
- **Loss Function**: Sparse Categorical Crossentropy  
- **Validation Split**: 10% of training data  
- **Framework**: TensorFlow & Keras  

---

## 📈 Results & Evaluation

- **Training Accuracy**: ~99.33%  
- **Validation Accuracy**: ~98.33%  
- **Test Accuracy**: ~98.38%

The model shows strong generalization on unseen data and performs well on handwritten digit classification tasks.
