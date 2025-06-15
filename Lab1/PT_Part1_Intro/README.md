

# 📘 PT\_Part1\_Intro.ipynb

## 🔍 Overview

This notebook is the **first lab** in the [MIT Introduction to Deep Learning 2025](http://introtodeeplearning.com) course. It serves as an **introduction to PyTorch** and key deep learning concepts. The notebook is designed for educational purposes and is structured to be beginner-friendly, with hands-on examples and explanations.

In this lab, students will:

* Learn the fundamentals of PyTorch tensors and operations
* Build simple neural network layers and models using PyTorch
* Understand automatic differentiation and backpropagation
* Apply gradient descent to minimize simple loss functions

---

## 📂 Notebook Structure

### 1. **Setup**

* Install required packages (`mitdeeplearning`, `torch`, etc.)
* Import necessary libraries

### 2. **Tensors in PyTorch**

* Introduction to `torch.tensor`
* Operations on scalars, vectors, matrices, and 4D tensors
* Tensor slicing and shape manipulation

### 3. **Tensor Computations**

* Visualize computations as graphs
* Define simple computation graphs in PyTorch
* Write functions that simulate computational graphs

### 4. **Building Neural Networks**

* Create custom dense layers using `nn.Module`
* Use PyTorch's `Sequential` API to stack layers
* Subclass `nn.Module` to build flexible models with custom behavior

### 5. **Automatic Differentiation**

* Use `requires_grad` and `backward()` to compute gradients
* Perform manual optimization using gradient descent
* Visualize convergence during optimization

---

## 🚀 How to Use

You can run this notebook directly in [Google Colab](https://colab.research.google.com/github/MITDeepLearning/introtodeeplearning/blob/master/lab1/PT_Part1_Intro.ipynb):

1. Open the notebook in Google Colab via the link above.
2. Run each cell sequentially.
3. Fill in the `TODO` blocks where indicated to complete the exercises.
4. Observe outputs and plots to understand tensor operations and training dynamics.

---

## 🔧 Requirements

* Python ≥ 3.7
* PyTorch ≥ 1.12
* `mitdeeplearning` package (installed via pip)
* NumPy and Matplotlib (preinstalled in Colab)

---

## 📜 License

This code is licensed under the **MIT License**. Any use or modification of the code outside the context of the MIT Introduction to Deep Learning course must reference:

> © MIT Introduction to Deep Learning
> [http://introtodeeplearning.com](http://introtodeeplearning.com)




