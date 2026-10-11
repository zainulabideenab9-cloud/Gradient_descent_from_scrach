# ⚡ Gradient Descent from Scratch

A compact Python project that implements linear regression using three optimization strategies from scratch:

- Batch Gradient Descent
- Stochastic Gradient Descent
- Mini-Batch Gradient Descent

The notebooks train on the scikit-learn Diabetes dataset and compare custom implementations against the built-in sklearn models to understand convergence and performance trade-offs.

## 📌 What this project covers

- Custom gradient descent implementations in NumPy
- Linear regression training and prediction
- Train/test split and model evaluation
- Real-world comparison of optimization strategies using the R² score

## 📁 Repository contents

- [batch_gradient_descent.ipynb](batch_gradient_descent.ipynb)
- [stochastic_gradient_descent.ipynb](stochastic_gradient_descent.ipynb)
- [Mini_batch_gradient_descent.ipynb](Mini_batch_gradient_descent.ipynb)
- [LICENSE](LICENSE)

## 🚀 Setup

```bash
pip install numpy pandas scikit-learn jupyter
jupyter notebook
```

Open the notebook you want to study and run the cells in order.

## 🧠 Learning goal

This project is designed to help understand how gradient descent works under different batch sizes and why each variant is useful for different data sizes and training scenarios.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
