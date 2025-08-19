# Digit Classifier (MNIST with PyTorch)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/silencer722/digit-classifier/blob/main/digit_class.ipynb)

This project trains a simple **logistic regression model** on the MNIST dataset (handwritten digits 0–9) using **PyTorch**.

## 🚀 Project Overview
- Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/)
- Model: Linear layer (Logistic Regression)
- Training: Mini-batch Gradient Descent
- Accuracy: ~92% on test data

## 📂 Files
- `digit_class.ipynb` → Jupyter Notebook with full code and training steps
- `requirements.txt` → Python dependencies

## ▶️ How to Run
You can open the notebook directly in Google Colab by clicking the badge above 👆.

Or run locally:
```bash
git clone https://github.com/silencer722/digit-classifier.git
cd digit-classifier
pip install -r requirements.txt
jupyter notebook digit_class.ipynb
