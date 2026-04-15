# Tensors – Quick Guide

## 📌 What is a Tensor?

A **tensor** is a multi-dimensional array used in mathematics and machine learning.

* 0D tensor → Scalar (single number)
* 1D tensor → Vector (array)
* 2D tensor → Matrix
* nD tensor → Higher-dimensional data

## 🧠 Why Tensors Matter

Tensors are the core data structure in deep learning frameworks like TensorFlow and PyTorch. They allow efficient computation on CPUs, GPUs, and TPUs.

## 📊 Examples

### Scalar (0D)

```
5
```

### Vector (1D)

```
[1, 2, 3]
```

### Matrix (2D)

```
[[1, 2],
 [3, 4]]
```

### 3D Tensor

```
[
  [[1,2],[3,4]],
  [[5,6],[7,8]]
]
```

## ⚙️ Tensor Operations

Common operations include:

* Addition
* Multiplication
* Reshaping
* Slicing
* Broadcasting

## 🚀 Example in Python

### Using TensorFlow

```python
import tensorflow as tf

tensor = tf.constant([[1, 2], [3, 4]])
print(tensor)
```

### Using PyTorch

```python
import torch

tensor = torch.tensor([[1, 2], [3, 4]])
print(tensor)
```

## 📦 Applications

* Machine Learning
* Deep Learning
* Computer Vision
* Natural Language Processing

## 📚 Further Reading

* Tensor basics in TensorFlow
* PyTorch tensor operations
* Linear algebra fundamentals

---

✨ This README is a beginner-friendly overview of tensors. Expand it with examples, visuals, or project-specific details as needed.
