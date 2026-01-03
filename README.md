# LinearRegression
# 📊 Advertising Sales Prediction using Machine Learning

## 📌 Project Overview
This project demonstrates an **end-to-end machine learning regression workflow** using **scikit-learn**.  
The goal is to build and compare multiple regression models to predict **sales based on advertising spending** across different channels, and then choose the best model based on performance and robustness. :contentReference[oaicite:1]{index=1}


## 🎯 Objective
To train several regression models, evaluate them using appropriate metrics, and select the **best-performing model** that balances accuracy and simplicity.


## 🧰 Tools & Technologies
- **Python**
- **scikit-learn** − ML training and evaluation  
- **Pandas & NumPy** − Data handling  
- **Matplotlib & Seaborn** − Visualizations  
- **joblib** − Model saving for deployment :contentReference[oaicite:2]{index=2}


## 📂 Dataset
The dataset (`Advertising.csv`) contains advertising spend (in thousands of dollars) across:
- **TV**
- **Radio**
- **Newspaper**

Target variable:
- **Sales**

Total records: **200** :contentReference[oaicite:3]{index=3}


## 📈 Project Workflow
1. Exploratory data analysis  
2. Train-test split  
3. Train multiple regression models  
4. Evaluate models using **MAE, MSE, RMSE**  
5. Visual comparison with graphs  
6. Select best model based on performance  
7. Save model for deployment :contentReference[oaicite:4]{index=4}


## 🤖 Implemented Models
- **Linear Regression**  
- **Polynomial Regression** (degree tuning)  
- **Lasso Regression** (L1 regularization)  
- **Ridge Regression** (L2 regularization with cross-validation) :contentReference[oaicite:5]{index=5}


## 📊 Model Evaluation & Selection
- Models were compared using training and test error metrics.  
- **Graphs** were used to inspect whether models were overfitting or underfitting.  
- Polynomial regression (degree 3) achieved low errors, but **Ridge Regression** was chosen because it offered equally strong performance **with better generalization and lower complexity**. :contentReference[oaicite:6]{index=6}


## 🚀 Deployment
The final trained model and feature transformer are saved as `.joblib` files:
- `AdvertisementModel.joblib`  
- `final_polynomial_converter.joblib`  

These can be loaded later for making new predictions. :contentReference[oaicite:7]{index=7}


## 🧠 Key Learnings
- Comparing multiple models helps find the right balance between accuracy and robustness  
- Visualization is essential for diagnosing underfitting and overfitting  
- Deployment (model saving) is a vital part of real-world ML pipelines


## 📌 Project Level
**Beginner | Practical ML Workflow | scikit-learn** :contentReference[oaicite:8]{index=8}


### ⭐ Feedback & Contributions
Feedback, suggestions, and improvements are welcome!

