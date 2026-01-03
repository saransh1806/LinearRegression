# LinearRegression
📌 Project Overview
This project is a beginner-level end-to-end Machine Learning regression project built using scikit-learn.
The goal is to predict sales based on advertising expenditure across different channels and understand model selection, evaluation, and deployment in a practical ML workflow.

🎯 Objective
To compare multiple regression models and select the best-performing and most robust model based on evaluation metrics and model complexity.

🧰 Tools & Technologies
Python

Pandas, NumPy

Matplotlib, Seaborn

scikit-learn

joblib

The dataset contains advertising spend across three channels:
TV

Radio

Newspaper

Target variable:Sales

Total records: 200

🔍 Project Workflow

Data loading and exploration

Visual analysis of advertising channels vs sales

Train-test split (70% training, 30% testing)

Feature scaling using StandardScaler

Training multiple regression models

Model evaluation using MAE, MSE, and RMSE

Model comparison and selection

Saving the final model for deployment

🤖 Models Implemented

Linear Regression

Polynomial Regression (degree tuning)

Lasso Regression (L1 regularization)

Ridge Regression (L2 regularization with cross-validation)

📊 Model Evaluation & Selection

Training and test errors were compared for all models

Training vs Test error graphs were used to identify overfitting and underfitting

Polynomial Regression (degree 3) achieved very low error

Ridge Regression showed nearly identical performance with lower model complexity

✅ Ridge Regression was selected as the final model due to its robustness and generalization ability.

Model Deployment

The final trained model and polynomial feature transformer were saved using joblib, allowing the model to be reused for future predictions.

Saved files:

AdvertisementModel.joblib
final_polynomial_converter.joblib
