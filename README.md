# Custom-Regression-Handled

Custom-handled regression models: Normal Equation, Gradient Descent, and SGD, built using NumPy.

# 📊 Custom Regression-Handled(From Scratch)

- This project implements Regression using three approaches:

  - Normal Equation (Closed Form)
  - Batch Gradient Descent (BGD)
  - Stochastic Gradient Descent (SGD)

Each is compared against Scikit-learn’s LinearRegression for validation.

# 🚀 Features

- Synthetic dataset generation (TV, Radio, Newspaper ads → Sales)
- Custom implementations with NumPy
- Feature scaling for gradient descent
- Side-by-side comparison with Scikit-learn

# 🛠️ Methods

- Normal Equation → Direct closed-form solution
- Batch Gradient Descent → Iterative updates using all samples
- Stochastic Gradient Descent → Updates using one sample at a time

# 📌 Example

- Fit Custom Models
  - custom_lin_reg = MyLinearRegression().fit(X, y)
  - custom_bgd = CustomBGDRegressor().fit(X_scaled, y)
  - custom_sgd = CustomSGDRegressor().fit(X_scaled, y)

- Compare with sklearn
  - from sklearn.linear_model import LinearRegression
  - lin_reg = LinearRegression().fit(X, y)


