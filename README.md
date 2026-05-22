
# ElasticNet Regression (From Scratch)

A custom implementation of the ElasticNet regression model in Python, combining L1 (Lasso) and L2 (Ridge) regularization.

---

## Project Overview

This project builds ElasticNet regression **from scratch** without relying on high-level ML libraries.

The goal is to:
- Understand regularization techniques  
- Handle multicollinearity  
- Improve model generalization  

---

## Key Features

### Custom ElasticNet Model
- Combines L1 (Lasso) and L2 (Ridge) penalties  
- Iterative coefficient optimization  
- Supports convergence control  

### Model Capabilities
- Fit model to training data  
- Predict target values  
- Evaluate performance  

### Evaluation Metrics
- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- R² Score  

### Visualization
- Actual vs Predicted values  
- Residual plots  

### Robust Testing
- Built using **pytest**
- Validates:
  - Prediction accuracy  
  - Edge cases (single feature, no variance)  
  - Convergence behavior  

---

## How It Works

1. Initialize model with parameters (alpha, l1_ratio)  
2. Train using iterative coefficient updates  
3. Apply L1 + L2 penalties during training  
4. Stop when convergence criteria is met  
5. Evaluate model using metrics  

---
