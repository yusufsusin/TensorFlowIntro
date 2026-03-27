# TensorFlow Fundamentals

A beginner-friendly notebook covering the core concepts of TensorFlow — from tensors and basic operations to building and training your first machine learning model.

---

## 📌 What is TensorFlow?

TensorFlow is an open-source machine learning framework developed by Google. It is widely used for building and training deep learning models across domains such as image recognition and natural language processing.

---

## 📓 Notebook Contents

| Section | Topic |
|---------|-------|
| 1 | Introduction & Setup |
| 2 | Creating Tensors |
| 3 | Basic Tensor Operations |
| 4 | Building a Linear Regression Model |

---

## 🔑 Key Concepts

### Tensors
The fundamental data structure in TensorFlow — multi-dimensional arrays similar to NumPy arrays. Two main types:
- `tf.constant` — fixed value, cannot be changed
- `tf.Variable` — mutable value, updated during training

### Tensor Operations
TensorFlow supports element-wise addition, multiplication, and matrix multiplication, all optimized for GPU execution.

### Linear Regression with Keras
The notebook trains a simple model to learn the relationship `y = 2x + 0.5` using:
- A single `Dense` layer
- SGD optimizer
- Mean Squared Error loss

---

## 🚀 Getting Started

### Requirements
```bash
pip install tensorflow numpy matplotlib
```

### Run the Notebook

Open in [Google Colab](https://colab.research.google.com) or run locally with Jupyter:
```bash
jupyter notebook TensorFlow_Mis48B.ipynb
```

---

## 📊 What You Will Build

A linear regression model trained on synthetic data that learns to predict outputs from inputs — the classic "Hello World" of machine learning.
```
Input (X): [0, 1, 2, 3, 4, 5]
True  (y): [0.5, 2.5, 4.5, 6.5, 8.5, 10.5]

Model learns: y = 2x + 0.5
```

After 500 epochs, the model's predictions are visualized against the true values.

---

## 🔗 Resources

- [TensorFlow Official Docs](https://www.tensorflow.org/learn)
- [Keras Documentation](https://keras.io)
- [TensorFlow Playground](https://playground.tensorflow.org)
