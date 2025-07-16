# 🚀 Moons Dataset Classification using Deep Neural Networks

This project implements a 3-layer deep neural network **from scratch using NumPy**, trained on the classic **moons dataset**.  
The model is optimized using three methods: **Gradient Descent, Momentum, and Adam** — to compare performance in terms of accuracy, convergence speed, and decision boundary quality.

---

## 📌 Objective

Classify two interleaving half circles (moons) using a custom neural network and observe how different optimization algorithms affect training.

---

## 🧠 Model Architecture

- Input layer → 5 neurons → 2 neurons → 1 output neuron
- Activation: ReLU (hidden layers), Sigmoid (output)
- Loss: Binary Cross-Entropy

---

## 🧪 Dataset: Moons

- Non-linear, two-class classification problem
- Generated using `sklearn.datasets.make_moons(n_samples=300, noise=0.2)`
- Class 0 (Blue) vs Class 1 (Red)

## ⚙️ Optimizers Implemented

- Gradient Descent (GD)
- Momentum
- Adam

Each optimizer is tested on the same model, and their **decision boundaries** and **accuracy** are compared.

---

## 📊 Optimizer Comparison

| Optimizer | Accuracy | Decision Boundary     | Speed of Convergence | Remarks             |
|-----------|----------|------------------------|----------------------|---------------------|
| GD        | 79.66%   | Linear / Rough         | Slow                 | Basic method        |
| Momentum  | 79.66%   | Smoother than GD       | Medium               | Uses velocity       |
| Adam      | **94%**  | Curved & Adaptive      | Fastest              | Best overall result |

---

## ✅ Learnings

- How different optimizers behave in training
- Why Adam typically performs better (adaptive learning + momentum)
- How decision boundaries reveal generalization power

------

