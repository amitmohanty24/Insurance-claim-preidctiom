# Predicting Insurance Claim Amounts Based on User Profile and Medical History

This project uses supervised machine learning techniques to predict health insurance claim amounts based on user demographics and medical history. The dataset includes features such as age, sex, BMI, number of children, smoking status, region, and charges.

## 📌 Problem Statement

Estimate the claim amount in health insurance using structured user profile data to assist insurers in pricing, risk assessment, and resource allocation.

---

## 🎯 Objective

To build machine learning models for accurately predicting medical insurance costs using the following regression algorithms:
- Linear Regression
- Random Forest Regressor

Model performance is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🛠️ Project Pipeline

1. Import required libraries  
2. Load and inspect the dataset  
3. Perform exploratory data analysis (EDA)  
4. Visualize key insights using graphs  
5. Preprocess and encode the data  
6. Apply feature scaling  
7. Split the dataset into training and testing sets  
8. Train regression models  
9. Evaluate model performance  
10. Compare models and draw conclusions

---

## 📂 Dataset Features

| Feature     | Description                                 |
|-------------|---------------------------------------------|
| `age`       | Age of the policyholder                     |
| `sex`       | Gender of the policyholder                  |
| `bmi`       | Body Mass Index                             |
| `children`  | Number of dependents                        |
| `smoker`    | Smoking status (yes/no)                     |
| `region`    | Residential region in the US                |
| `charges`   | Health insurance claim amount (target)      |

---

## 📊 Visualizations

- Distribution of charges across age, BMI, and smoking status
- Box plots to show correlation between categorical variables and charges
- Heatmap of feature correlation

---

## 🔍 Models Used

- **Linear Regression**: Simple, interpretable model to establish baseline performance.
- **Random Forest Regressor**: Ensemble method to improve accuracy using decision trees.

---

## ✅ Evaluation Metrics

| Metric | Description |
|--------|-------------|
| MAE | Average absolute difference between predicted and actual values |
| MSE | Average squared difference between predicted and actual values |
| RMSE | Square root of MSE, penalizes larger errors |
| R² Score | Percentage of variance in `charges` explained by the model |

---

## 🧾 Conclusion

- **Random Forest Regressor** outperforms Linear Regression in prediction accuracy.
- **Smoker status**, **BMI**, and **age** are the most significant predictors of insurance charges.
- The model provides useful insights for insurance companies to better estimate claim amounts.

---

## 🧠 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn

## made by Amit Mohanty

