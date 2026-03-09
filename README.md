# Customer Churn Prediction

This project predicts whether a **telecom customer will leave the company (churn)** using a Machine Learning classification model.

Customer churn prediction helps companies **identify customers who are likely to leave** so they can take actions to retain them.

The model is trained on the **Telco Customer Churn dataset** and achieves an accuracy of approximately **82%**.

---

## Technologies Used

- **Python**
- **NumPy** – numerical operations  
- **Pandas** – data cleaning and manipulation  
- **Matplotlib** – data visualization  
- **Seaborn** – statistical visualization  
- **Scikit-learn** – machine learning algorithms  

---

## Project Workflow

### 1. Data Cleaning
- Loaded dataset using **Pandas**
- Removed unnecessary columns like `customerID`
- Checked for missing values

### 2. Exploratory Data Analysis (EDA)
- Used **Seaborn and Matplotlib** to visualize patterns
- Analyzed relationships between:
  - Churn vs Monthly Charges
  - Churn vs Tenure
  - Churn distribution

### 3. Feature Engineering
- Converted categorical variables into numeric values using **One-Hot Encoding**
- Prepared dataset for machine learning models

### 4. Model Training
- Applied **Logistic Regression** using **Scikit-learn**
- Split dataset into **training and testing sets**

### 5. Model Evaluation
- Evaluated model using **Accuracy Score**

---

## Model Performance

**Accuracy:** ~82%

This means the model correctly predicts churn for about **82% of customers**.

---

## Author

**Mubarak**

GitHub:  
https://github.com/Mubarak-04
