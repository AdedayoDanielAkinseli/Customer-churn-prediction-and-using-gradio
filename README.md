# 📉 Customer Churn Prediction using Machine Learning and Gradio  

### 📘 Overview  
This project predicts **customer churn** — whether a customer will stop using a company’s services — using demographic, account, and transaction data.  
It also features an **interactive Gradio web interface** that allows users to test predictions in real-time.

---

### 🎯 Objectives  
- Analyze customer data to identify churn risk patterns.  
- Build and evaluate predictive models for churn classification.  
- Deploy the model using a **Gradio** app for easy user interaction.  
- Provide actionable insights to improve customer retention strategies.

---

### ⚙️ Workflow  

#### 1. Data Preprocessing  
- Cleaned missing values and removed irrelevant features.  
- Encoded categorical variables and scaled numeric attributes.  
- Balanced the dataset using **SMOTE** to address class imbalance.

#### 2. Model Development  
- Implemented **Logistic Regression**, **Random Forest**, and **XGBoost** models.  
- Tuned hyperparameters using **GridSearchCV** for optimal accuracy.  
- Selected the best-performing model based on validation metrics.

#### 3. Model Deployment  
- Integrated the final model into a **Gradio** app.  
- Created a simple UI for real-time churn prediction.  
- Users can input customer details and get instant predictions.

---

### 🧠 Tools & Libraries  
- **Python**, **Pandas**, **NumPy**, **Scikit-learn**, **XGBoost**  
- **Gradio**, **Matplotlib**, **Seaborn**

---

### 📊 Results  
- Achieved **~85% accuracy** on the test dataset.  
- Balanced precision and recall for reliable churn detection.  
- Identified key features: **tenure**, **monthly charges**, and **contract type**.

---

### 💡 Insights  
- Customers with short tenures or month-to-month contracts are more likely to churn.  
- Regular model retraining can help maintain prediction accuracy.  
- Business teams can use these insights to design better loyalty programs.

---

### 📁 Dataset  
- **Source:** [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)  
- **Rows:** 7,043  
- **Target Variable:** `Churn` → `Yes` or `No`

---

### 🚀 Future Improvements  
- Integrate the model into a **Streamlit dashboard** for richer visualization.  
- Add **automated retraining** on new data.  
- Include **SHAP** values for explainable predictions.

---

### 🖥️ Gradio App Preview  
You can launch the app by running:
```bash
python app.py

