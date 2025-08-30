# Handwritten-digit-recognition
# 🔢 Handwritten Digit Recognition (MNIST)

A Deep Learning project using **Convolutional Neural Networks (CNNs)** to recognize handwritten digits (0–9) from the **MNIST dataset** with over **98% accuracy**.

---

## 🚀 Problem Statement
Handwritten text varies widely, making it difficult for machines to read.  
This project demonstrates how AI can recognize handwritten digits, which is useful in education tech, exam-checking tools, and document digitization.

---

## 🎯 Objective
- Use CNNs to classify handwritten digits from the MNIST dataset.  
- Train, validate, and test the model for high accuracy.  
- (Optional) Build a simple UI to draw digits and predict them.  

---

## 📂 Dataset
We use the **MNIST dataset** (70,000 grayscale images of digits, 28x28 pixels each).  

- 60,000 training images  
- 10,000 test images  

It is available directly in **TensorFlow/Keras**:
```python
from tensorflow.keras.datasets import mnist
