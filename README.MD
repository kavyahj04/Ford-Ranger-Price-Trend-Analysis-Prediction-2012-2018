# Edge of Stability — Ford Ranger Price Trend Analysis

Linear regression model built from scratch to analyze and predict Ford Ranger prices (2012–2018) using gradient descent with and without feature scaling.

## What This Project Does

- Implements linear regression manually using NumPy (no sklearn)
- Predicts missing Ford Ranger prices for 2012–2018
- Compares baseline (unscaled) vs feature-scaled gradient descent
- Uses dynamic learning rate for faster convergence
- Predicts 2026 Ford Ranger price range: **$27,119 – $42,608**

## Tech Stack
- Python
- NumPy
- Matplotlib
- Google Colab

## Key Results

| Year | Predicted Min | Predicted Max |
|------|--------------|---------------|
| 2012 | $17,427 | $28,882 |
| 2015 | $19,504 | $31,823 |
| 2018 | $21,581 | $34,765 |
| 2026 | $27,119 | $42,608 |

## Concepts Covered
- Gradient descent (manual implementation)
- Feature scaling / standardization
- Dynamic learning rate
- Loss curve visualization
- Linear hypothesis function: `f(x) = θ₀ + θ₁x`

## How to Run

Open `Project_01.ipynb` in Google Colab and run all cells.
