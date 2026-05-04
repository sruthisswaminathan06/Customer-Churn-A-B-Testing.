# 📉 Customer Churn Prediction — Machine Learning Project  
Predicting customer churn using simulated telecom data with **Pandas**, **Scikit‑Learn**, and **Matplotlib**.

---

## 📌 Project Overview  
This project demonstrates an end‑to‑end **Customer Churn Prediction** workflow.  
It covers:

- 🔹 Simulating a telecom churn dataset  
- 🔹 Cleaning & encoding categorical variables  
- 🔹 Training **Logistic Regression** & **Random Forest** models  
- 🔹 Evaluating performance using classification reports, confusion matrices & ROC curves  
- 🔹 Visualizing model performance  

This project is ideal for showcasing **machine learning**, **data preprocessing**, and **model evaluation** skills.

---

## 🧠 Problem Statement  
Telecom companies lose significant revenue when customers discontinue their services.  
The goal of this project is to:

> **Build predictive models that classify whether a customer is likely to churn.**

This helps businesses take proactive retention actions.

---

## 📂 Dataset  
Since no real dataset was provided, a **synthetic dataset of 1000 customers** was generated using NumPy.

### Features include:
- `gender`
- `SeniorCitizen`
- `Partner`
- `Dependents`
- `tenure`
- `PhoneService`
- `InternetService`
- `MonthlyCharges`
- `TotalCharges`
- `Churn` (target)

### Example (from your notebook):
> “0 Male 1 Yes No 6 No DSL 97.95 3501.24 Yes”  
> “1 Female 0 No No 34 No No 21.62 5273.29 Yes”

---

## 🧹 Data Preprocessing  
Steps performed:

### ✔ Label Encoding  
Categorical columns encoded using `LabelEncoder`:

```
['gender','Partner','Dependents','PhoneService','InternetService','Churn']
```

### ✔ Train–Test Split  
- 70% training  
- 30% testing  
- `random_state=42` for reproducibility  

---

## 🤖 Machine Learning Models  

### 1️⃣ Logistic Regression  
- Trained with `max_iter=1000`  
- Baseline linear model for classification  

### 2️⃣ Random Forest Classifier  
- 100 trees  
- Captures nonlinear relationships  

---

## 📊 Model Evaluation  

### **Logistic Regression Results**
```
Accuracy: ~0.50
Precision/Recall: Balanced around 0.50
```

### **Random Forest Results**
```
Accuracy: ~0.52
Slightly better performance than Logistic Regression
```

### Why accuracy is low?
Because the dataset is **randomly simulated**, not real-world structured data.  
The goal is to demonstrate the **pipeline**, not achieve high accuracy.

---

## 📈 Visualizations  
The notebook includes:

- ROC curves  
- Confusion matrices  
- Side‑by‑side model comparison  

Example (from your notebook):

> “<Figure size 600x400 with 2 Axes>”

---

## 🛠 Tech Stack  
| Category | Tools |
|---------|-------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Modeling | Scikit‑Learn |
| Visualization | Matplotlib |
| Notebook | Jupyter |

---

## 🚀 How to Run the Project  

### 1. Clone the repository  
```
git clone https://github.com/yourusername/customer-churn-project.git
```

### 2. Install dependencies  
```
pip install -r requirements.txt
```

### 3. Run the notebook  
```
jupyter notebook
```

---

## 📚 Key Learnings  
- How to simulate realistic datasets  
- Encoding categorical variables  
- Training baseline ML models  
- Evaluating classification performance  
- Visualizing model metrics  

---

## 📌 Future Improvements  
- Use real telecom churn dataset  
- Add feature engineering  
- Hyperparameter tuning (GridSearchCV)  
- Try advanced models (XGBoost, LightGBM)  
- Deploy using Flask/Streamlit  

---

## 🏁 Conclusion  
This project provides a complete, professional pipeline for **customer churn prediction**.  
It demonstrates your ability to:

- Build ML workflows  
- Clean and encode data  
- Train & evaluate models  
- Visualize insights  

