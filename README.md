# Comparative Analysis of Regression Models on Boston Housing Dataset

This project explores the performance of various regression models—**Lasso**, **OLS**, **Ridge**, and **KNN**—on the Boston Housing dataset. The goal is to compare their predictive accuracy and understand how different hyperparameters affect their performance.

## Models Implemented:
1. **K-Nearest Neighbors (KNN) Regression**:
   - Evaluated R² scores for different values of `k` (number of neighbors).
   - Plotted training and testing R² scores to analyze overfitting/underfitting.

2. **Lasso Regression**:
   - Tested various alpha (regularization strength) values.
   - Analyzed training and testing errors (MSE) and R² scores.
   - Identified the optimal alpha value for the dataset.

3. **Ordinary Least Squares (OLS) Regression**:
   - Computed R² scores and Mean Squared Error (MSE) for training and testing data.
   - Visualized residuals to assess model performance.

4. **Ridge Regression**:
   - Explored the impact of alpha values on model performance.
   - Compared training and testing errors (MSE) and R² scores.
   - Determined the optimal alpha value for the dataset.

## Key Insights:
- **KNN**: Performance varies significantly with the choice of `k`. Smaller `k` values tend to overfit, while larger `k` values may underfit.
- **Lasso**: Regularization helps reduce overfitting, and the optimal alpha value balances bias and variance.
- **OLS**: Simple and interpretable but may overfit if the dataset has multicollinearity.
- **Ridge**: Similar to Lasso but retains all features, making it useful when all predictors are relevant.

## Dataset:
- **Boston Housing Dataset**: Contains features such as crime rate, average number of rooms, and accessibility to highways, with the target variable being the median value of owner-occupied homes (MEDV).

## Code Structure:
- Each model is implemented in a separate script or notebook.
- Visualizations include:
  - R² scores vs. hyperparameters (e.g., `k` for KNN, `alpha` for Lasso/Ridge).
  - Residual plots for OLS.
  - Training vs. testing error plots.

## Requirements:
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## How to Use:
1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the scripts for each model to reproduce the analysis.

## Results:
- Detailed performance metrics (R², MSE) for each model.
- Visualizations to compare model behavior across different hyperparameters.

## Paper:
For a detailed analysis and discussion of the results, refer to the accompanying paper:  
[**Analysis.pdf**]([docs/Homework1_Khangai.pdf](https://docs.google.com/document/d/1gZQRm7fY9kgEe0kDUZGP1GdAZi0X8gkNhoIQ3-mWhD0/edit?usp=sharing))  
*(Click the link to view the paper.)*

## Graph📈 :

![Screenshot 2025-02-22 at 8 00 37 PM](https://github.com/user-attachments/assets/a4a85cd0-c253-4f39-9c4c-a81a0c167375)
![Screenshot 2025-02-22 at 7 49 24 PM](https://github.com/user-attachments/assets/cdf45bb1-cdaf-4af9-a24f-61aeea56f6be)
![Screenshot 2025-02-21 at 7 54 36 AM](https://github.com/user-attachments/assets/16ce859e-8f86-41cd-a439-5193b3d99397)
![Screenshot 2025-02-19 at 6 08 36 PM](https://github.com/user-attachments/assets/4c0c6505-1cc9-4f22-8d9f-54f9b65807d0)
![Screenshot 2025-02-19 at 4 14 45 PM](https://github.com/user-attachments/assets/2cfc8a3f-9b44-48bd-a29c-10fcba9a8c8e)

<img width="843" alt="Screenshot 2025-02-24 at 10 51 48 PM" src="https://github.com/user-attachments/assets/866e776b-66c5-499f-9085-6e7d4aa3c2e7" />
<img width="838" alt="Screenshot 2025-02-24 at 10 51 28 PM" src="https://github.com/user-attachments/assets/30d09bfd-2e57-4f2c-8497-7fa8713bff06" />



## Future Work:
- Explore additional models (e.g., Random Forest, Gradient Boosting).
- Perform feature engineering to improve model performance.
- Conduct cross-validation for more robust results.

  
