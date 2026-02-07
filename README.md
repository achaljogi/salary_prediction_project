# 💼 Salary Prediction using Machine Learning  
**Tech Stack:** MySQL • Snowflake • Python (Pandas, Scikit-learn, Matplotlib)

## 📌 Project Overview
This project demonstrates an **end-to-end data pipeline** for predicting salaries using Machine Learning.  
The workflow covers **data engineering, data analytics, and machine learning** using a Kaggle salary dataset.

Pipeline flow:  
**MySQL → Snowflake → Python (Machine Learning)**

The goal is to build a regression model that predicts **Salary_USD** and evaluate its performance using standard metrics.

---

## 🧰 Tools & Technologies
- **Database:** MySQL, Snowflake  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib  
- **IDE/Tools:** MySQL Workbench, Jupyter Notebook / VS Code  

---

## 📊 Dataset
- Source: Kaggle Salary Dataset  
- Contains features related to job roles, experience, location, etc.  
- Target variable: **Salary_USD**

---

## 🔄 Project Workflow

### 1️⃣ Data Loading (MySQL)
- Loaded the dataset into **MySQL** using MySQL Workbench  
- Performed **data cleaning and preprocessing**  
- Executed SQL queries for **Exploratory Data Analysis (EDA)**:
  - `COUNT`
  - `AVG`
  - `GROUP BY`
  - Filtering and aggregation queries

### 2️⃣ Data Migration (Snowflake)
- Exported cleaned data from MySQL to **Snowflake**  
- Performed:
  - Cloud-based transformations  
  - Data validation and consistency checks  

### 3️⃣ Machine Learning (Python)
- Imported data into Python using **Pandas**  
- Performed:
  - Feature selection
  - Data preprocessing
- Built a **Linear Regression** model using **Scikit-learn** to predict `Salary_USD`

### 4️⃣ Model Evaluation & Visualization
- Evaluated model performance using:
  - **MAE (Mean Absolute Error)**
  - **MSE (Mean Squared Error)**
  - **R² Score**
- Visualized **Actual vs Predicted Salary** using **Matplotlib**

---

## 📈 Results
- Successfully built a regression model to predict salaries  
- Model performance measured using MAE, MSE, and R² Score  
- Visualization shows the relationship between actual and predicted values  
- Demonstrates a complete **data pipeline + analytics + ML workflow**

---

## 🏗️ Project Structure

├── data/
│ └── dataset.csv
├── sql/
│ └── eda_queries.sql
├── notebooks/
│ └── salary_prediction.ipynb
├── README.md
└── requirements.txt


