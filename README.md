#  HR Attrition Analysis & Prediction System

---

##  Project Objective

The goal of this project is to analyze employee data and understand the key factors that influence employee attrition (turnover). The project also builds machine learning models to predict whether an employee is likely to leave the company.

This helps HR departments take early action and improve employee retention.

---

##  Business Problem

Employee turnover is costly for organizations.
This project answers:

* Why do employees leave?
* Which employees are at risk?
* Can we predict attrition in advance?

---

##  Dataset

IBM HR Analytics Attrition Dataset

It contains employee information such as:

* Age, Salary, Job Role
* Job Satisfaction, Work-Life Balance
* Overtime, Experience
* Attrition (Target Variable)

---

##  Project Workflow

### 1. Data Preprocessing

* Removed irrelevant columns (EmployeeNumber, StandardHours, etc.)
* Handled categorical variables using encoding
* Scaled numerical features using StandardScaler

---

### 2. Unsupervised Learning (Clustering)

* Applied K-Means Clustering
* Used Elbow Method to determine optimal clusters (K=5)
* Grouped employees into behavioral segments

---

### 3. Visualization

* Used PCA for dimensionality reduction
* Visualized employee clusters in 2D space

---

### 4. Supervised Learning (Prediction)

Built classification models:

* Logistic Regression
* Random Forest Classifier

---

##  Model Performance

### Logistic Regression

* Accuracy: ~72%
* Recall (Attrition): ~56%

### Random Forest

* Accuracy: ~88%
* Recall (Attrition): ~10%

---

##  Key Insights

* Employees with low job satisfaction and high overtime are more likely to leave
* Higher job level and income lead to better retention
* Clustering reveals hidden employee segments
* Logistic Regression performs better for detecting at-risk employees

---

##  Final Conclusion

Although Random Forest has higher accuracy, Logistic Regression is more effective for HR attrition prediction because it better identifies employees likely to leave.

In HR problems, **recall is more important than accuracy**.

---

##  Skills Demonstrated

* Python (Pandas, NumPy)
* Data Cleaning & Preprocessing
* Feature Engineering
* K-Means Clustering
* Logistic Regression
* Random Forest
* Model Evaluation (Accuracy, Precision, Recall)
* PCA Visualization

---

##  Project Impact

This system can help HR departments:

* Identify high-risk employees
* Reduce employee turnover
* Improve workforce planning
* Make data-driven HR decisions

---

##  Author

AI Student | Machine Learning Enthusiast | Python Developer

