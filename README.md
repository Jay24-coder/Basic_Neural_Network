# 🔢 Activation Functions & Gradient Descent Visualization

This repository demonstrates the working of basic activation functions and gradient descent in a simple linear model. It covers the concepts of **Sigmoid**, **tanh**, and **ReLU** activation functions, along with a hands-on implementation of a basic training loop using gradient descent.

---

## 📌 Description

The notebook contains:

### ✅ Activation Functions Overview

- **Sigmoid Function**  
  Outputs values between **0 and 1**. Suitable for binary classification and probabilistic outputs. Commonly used in the **output layer** of models.

- **tanh Function**  
  Outputs values between **-1 and 1**. Offers zero-centered output which can improve training convergence. Used in **hidden layers**.

- **ReLU (Rectified Linear Unit) Function**  
  Outputs values from **0 to ∞**. Helps tackle the vanishing gradient problem. Commonly used in **hidden layers** of deep learning models.

### ✅ Gradient Descent Implementation

A simple linear equation is trained using gradient descent:

\[
y = 3x_1 + 4x_2
\]

**Goal:** Minimize the error between predicted and actual `y` using weight updates.

#### Key Components:

- Random initialization of weights (`w1`, `w2`)
- Loss: **Mean Squared Error**
- Weight updates using **gradient descent**
- Visualization of:
  - Error reduction over epochs
  - Predictions over epochs

---

## 📊 Outputs

Two plots are generated to visualize training:

- **Error Graph** – Shows how the error decreases across 20 epochs.
- **Prediction Graph** – Displays the change in predictions (`y_pred`) across training iterations.

---

## 🛠️ Technologies Used

- Python 3.x
- NumPy
- Matplotlib

---

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/activation-functions-gradient-descent.git

```

2. Install required packages:
```
pip install numpy matplotlib

```

3. Run the notebook in Jupyter or any Python IDE that supports .ipynb

---


