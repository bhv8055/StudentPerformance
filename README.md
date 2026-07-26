# 🎓 Student Performance Prediction System

## 📌 Project Overview

The **Student Performance Prediction System** is a machine learning project designed to analyze student academic data and predict mathematics performance using demographic, educational, and examination-related features. The project applies data preprocessing, exploratory data analysis (EDA), feature engineering, regression modeling, and model evaluation to generate insights that can support educators in identifying factors influencing student success.

---

## 🎯 Problem Statement

Educational institutions collect large amounts of student performance data, but transforming this data into actionable insights remains challenging. This project aims to build a predictive analytics solution capable of estimating student mathematics scores while identifying the variables that contribute most to academic performance.

---

## 🎯 Objectives

* Analyze student academic performance data.
* Identify relationships between demographic and educational factors.
* Predict mathematics scores using machine learning.
* Compare multiple regression algorithms.
* Evaluate model performance using standard regression metrics.
* Generate insights that can assist educational decision-making.

---

# 📂 Dataset

**Dataset:** Students Performance Dataset

The dataset contains information about:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score
* Mathematics Score (Target Variable)

---

# 🛠️ Technologies Used

| Category                | Technologies          |
| ----------------------- | --------------------- |
| Programming Language    | Python                |
| Data Processing         | Pandas, NumPy         |
| Visualization           | Matplotlib, Seaborn   |
| Machine Learning        | Scikit-learn, XGBoost |
| Hyperparameter Tuning   | GridSearchCV          |
| Development Environment | Jupyter Notebook      |

---

# 📊 Exploratory Data Analysis

The project includes comprehensive EDA to understand student performance patterns.

### Analysis Performed

* Missing Value Analysis
* Correlation Analysis
* Feature Distribution
* Gender-wise Performance
* Parent Education Analysis
* Lunch Type Comparison
* Test Preparation Impact
* Reading vs Writing Relationship
* Outlier Detection
* Feature Correlation Heatmap

---

# ⚙️ Machine Learning Workflow

```text
Dataset
     │
     ▼
Data Cleaning
     │
     ▼
Feature Encoding
     │
     ▼
Train-Test Split
     │
     ▼
Model Training
     │
     ▼
Hyperparameter Tuning
     │
     ▼
Model Evaluation
     │
     ▼
Performance Comparison
```

---

# 🤖 Machine Learning Models

The following regression models were implemented and compared:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

Each model was evaluated using regression metrics to determine predictive performance.

---

# 📈 Model Evaluation

Evaluation metrics include:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

Hyperparameter tuning was performed to improve model performance.

---

# 📌 Key Insights

* Reading and writing scores are strong predictors of mathematics performance.
* Students completing the test preparation course generally achieve higher scores.
* Parental education level shows a positive relationship with academic performance.
* Lunch type demonstrates measurable differences in student outcomes.
* Feature importance analysis highlights the variables contributing most to prediction accuracy.

---

# 📷 Project Screenshots

Add screenshots after creating them.

```
screenshots/

├── correlation_heatmap.png
├── feature_importance.png
├── model_comparison.png
├── residual_plot.png
└── dashboard.png
```

---

# 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/bhv8055/studentassessment.git
```

Navigate to the project directory

```bash
cd studentassessment
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
StudentPerformance.ipynb
```

Run all cells.

---

# 📁 Project Structure

```
StudentPerformance/

│── data/
│── notebooks/
│── models/
│── dashboard/
│── screenshots/
│── requirements.txt
│── README.md
│── LICENSE
```

---

# 📌 Future Enhancements

* Deploy the prediction model using Streamlit.
* Build an interactive Power BI dashboard.
* Add Explainable AI (SHAP) visualizations.
* Implement model persistence using Joblib.
* Integrate SQL for educational analytics.
* Deploy the application to the cloud.

---

# 💼 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning
* Regression Analysis
* Hyperparameter Tuning
* Model Evaluation
* Data Visualization
* Python Programming
* Predictive Analytics

---

# 👨‍💻 Author

**Bharath Venkatesh**

B.Tech Computer Science & Engineering (Data Science)

Presidency University, Bengaluru

GitHub: https://github.com/bhv8055

---

## ⭐ If you found this project useful, consider giving the repository a star.
