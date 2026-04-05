# 🎓 Student Performance Analysis & Prediction (Python, Visualization & ML)

## 📌 Overview

This project performs **end-to-end analysis of student performance data**, including:

* Exploratory Data Analysis (EDA)
* Data Visualization (Matplotlib & Seaborn)
* Machine Learning (Logistic Regression)

The goal is to understand the factors influencing student success and build a model to **predict whether a student will pass or fail**.

---

## 🎯 Key Learning Outcomes

* Data exploration using Pandas
* Data visualization using Matplotlib and Seaborn
* Feature engineering and preprocessing
* Building and evaluating a classification model
* Interpreting model outputs and feature importance

---

# 📊 Task 1 — Data Exploration (EDA)

### 🔍 Objective

Understand dataset structure and identify patterns.

### ⚙️ Key Steps

* Loaded dataset using Pandas
* Checked data shape and types
* Generated summary statistics using `.describe()`
* Computed pass/fail distribution
* Compared subject-wise averages for passing vs failing students
* Identified top-performing student based on overall average

### 💡 Key Insight

Passing students consistently scored higher across all subjects, indicating strong predictive signals for the ML model.

---

# 📈 Task 2 — Data Visualization (Matplotlib)

### 🔍 Objective

Visualize trends and relationships in student data.

### 📊 Plots Created

* **Bar Chart** → Average score per subject
* **Histogram** → Distribution of math scores
* **Scatter Plot** → Study hours vs average score (Pass vs Fail)
* **Box Plot** → Attendance distribution (Pass vs Fail)
* **Line Plot** → Math vs Science scores per student

### 💡 Key Insights

* Study hours and attendance show strong correlation with performance
* Passing students cluster at higher score ranges
* Subject performance trends are consistent across high-performing students

---

# 🎨 Task 3 — Data Visualization (Seaborn)

### 🔍 Objective

Create more advanced statistical visualizations with less code.

### 📊 Plots Created

* Bar plots comparing math and science scores (Pass vs Fail)
* Scatter plot with regression lines showing relationship between attendance and performance

### 💡 Comparison (Seaborn vs Matplotlib)

* Seaborn simplifies statistical plotting and automatically handles grouping and styling
* Matplotlib provides more control but requires more manual configuration
* Seaborn is faster for exploratory analysis, while Matplotlib is better for customization

---

# 🤖 Task 4 — Machine Learning Model

### 🔍 Objective

Predict whether a student will pass or fail.

### ⚙️ Workflow

#### ✔ Data Preparation

* Selected features:

  * Subject scores
  * Attendance percentage
  * Study hours
* Split data into training (80%) and testing (20%)
* Scaled features using `StandardScaler`

#### ✔ Model Training

* Used `LogisticRegression`
* Achieved training accuracy based on dataset

#### ✔ Model Evaluation

* Evaluated on test set (small dataset → variable accuracy expected)
* Compared actual vs predicted labels for each student

#### ✔ Feature Importance

* Extracted model coefficients
* Visualized importance using horizontal bar chart
* Identified strongest predictors of performance

#### ✔ New Prediction

* Predicted outcome for a new student
* Displayed probability of passing vs failing

---

## 📊 Feature Importance Interpretation

* Positive coefficients → increase likelihood of passing
* Negative coefficients → increase likelihood of failing

### 💡 Key Insight

Features like **study hours, attendance, and subject scores** strongly influence student success.


# 🚀 Future Enhancements

* Use larger dataset for better model performance
* Try advanced models (Random Forest, XGBoost)
* Add cross-validation
* Build dashboard for visualization (Tableau / Streamlit)
* Deploy model as an API

---

# 🧠 Real-World Relevance

This project mirrors real-world workflows in:

* Data analytics and BI
* Predictive modeling
* Educational analytics systems
* Performance tracking platforms

---

# 👩‍💻 Author

**Ekta Tiwari**

---

## 🌟 Final Note

This project demonstrates how data can be transformed into actionable insights and predictions using Python, visualization tools, and machine learning techniques.
