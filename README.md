# 🧠 Fashion-MNIST Warm-up Project

**Course:** Project – Data Science and Artificial Intelligence (WiSe 2025/26)  
**Task:** Warm-up 1 – Fashion-MNIST  
**Author:** Aqsa Mohsin  

---

## 📘 Overview
This project is the first warm-up assignment for the Data Science and AI course.  
It focuses on building an image classification model for the **Fashion-MNIST** dataset,  
which contains 70,000 grayscale images of clothing items from 10 different categories.

The aim was to understand practical aspects of:
- Setting up the PyTorch environment  
- Data loading, preprocessing, and splitting  
- Implementing and comparing classical ML and deep learning models  
- Tracking performance metrics and visualizing diagnostics  

---

## 🧩 Models Implemented
1. **Logistic Regression (Baseline)**  
   - Flattened pixel input  
   - Achieved ~79% accuracy  
   - Good for simple, linearly separable classes  

2. **Neural Network (PyTorch)**  
   - 3 fully connected layers with ReLU activations and Dropout  
   - Achieved ~88% accuracy on test data  
   - Better generalization and feature learning  

---

## 📊 Results Summary
| Model | Accuracy | Notes |
|:------|:----------|:------|
| Logistic Regression | ~79% | Struggled with similar-looking classes (shirts, coats) |
| Neural Network | ~88% | Improved feature extraction and reduced confusion |

Key observations:
- Linear models are limited for complex texture differences.  
- Neural networks learn richer representations even with basic architectures.  
- Misclassifications mainly occur among visually similar classes.

---

## 📈 Visualizations
- Confusion Matrix for both models  
- Training vs Validation Loss curves  
- Accuracy comparison chart  
- Sample misclassifications  

---

## ⚙️ Requirements
- Python 3.10+  
- PyTorch  
- torchvision  
- scikit-learn  
- matplotlib  
- numpy  

Install dependencies:
```bash
pip install torch torchvision scikit-learn matplotlib numpy
