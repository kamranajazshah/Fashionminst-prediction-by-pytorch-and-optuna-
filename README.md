# Fashionminst-prediction-by-pytorch-and-optuna-
This project demonstrates how to build and optimize a neural network for fashion image classification using the FashionMNIST dataset. The model is implemented using **PyTorch**, and **Optuna** is used for automated hyperparameter tuning.

---

## 🚀 Features

- CNN-based architecture built with PyTorch
- Hyperparameter tuning using Optuna
- GPU support for faster training
- Live model performance metrics
- Customizable training pipeline

---

## 🛠️ Technologies Used

- Python 🐍
- PyTorch 🔥
- Optuna ⚙️
- Jupyter Notebook 📓

---

## 📁 Project Structure

📦FashionMNIST-PyTorch-Optuna ┣ 📄fashion_optuna.ipynb # Main notebook with model and tuning logic ┣ 📄requirements.txt # Required Python libraries ┗ 📄README.md # This file



## 📊 Dataset

We use the **FashionMNIST** dataset provided by `torchvision.datasets`. It contains 28x28 grayscale images of 10 fashion categories such as sneakers, shirts, trousers, etc.

---

## 📈 Hyperparameter Optimization with Optuna

Optuna automatically searches for the best combination of:
- Number of neurons
- Number of layers
- Dropout rate
- Learning rate
- Weight decay
- Batch size
- Optimizer choice
- Number of training epochs

Each trial is evaluated based on validation accuracy.
