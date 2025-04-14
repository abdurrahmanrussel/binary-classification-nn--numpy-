# Neural Network from Scratch using NumPy

This project implements a simple feedforward neural network **from scratch** using only `NumPy` — no deep learning frameworks like TensorFlow or PyTorch. It learns to classify 2D points into two classes using a **hidden layer** and the **sigmoid activation function**.

---

##  Overview

- Binary classification problem
- Input data: 2D points with a bias term
- Target:  
  `y = 1` if `|x₁| + |x₂| < 1`  
  `y = 0` otherwise
- Architecture:
  - 3 input nodes (2 features + bias)
  - 1 hidden layer with 4 neurons (sigmoid)
  - 1 output node (sigmoid)

---

## 🧾 Files

-  Jupyter Notebook — main training script
- `README.md` — this file
- Plots:
  - Loss & accuracy curves during training
  - Prediction visualization with true positives/negatives and errors

---

## 🛠 Requirements

- Python 3.x
- NumPy
- Matplotlib

Install using:

```bash
pip install numpy matplotlib
