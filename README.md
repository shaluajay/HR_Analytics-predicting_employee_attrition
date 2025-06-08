# HR Analytics - Predict Employee Attrition

##  Objective
Use analytics and machine learning to understand the key drivers behind employee attrition. The project also aims to provide actionable recommendations to reduce attrition.

---

## 🛠️ Tools & Technologies
- **Programming Language**: Python
- **Libraries**: pandas, seaborn, sklearn, matplotlib, shap
- **Visualization**: Power BI
- **Model**:  Decision Tree Classifier


##  Process Overview

### 1. Exploratory Data Analysis (EDA)
- Department-wise attrition
- Attrition by salary band and job role
- Age group and attrition trends
- Gender and marital status segmentation

### 2. Model Building
- Data preprocessing and train-test split
- Built classification model (Logistic Regression / Decision Tree)
- Evaluated using accuracy, confusion matrix, and classification report

### 3. Model Evaluation
- **Accuracy**: 84.6%
- **Confusion Matrix**:
[[361 19]
[ 49 12]]
 #### The model predicts non-attrition cases well but underperforms on predicting actual leavers due to class imbalance.

### 4. Explainability
- SHAP values used to interpret feature influence on predictions

### 5. Visualization
- Created interactive Power BI Dashboard to analyze:
- Attrition by department, salary, age, and job role
- Distribution of attrition across demographics


##  Key Insights (From Power BI Dashboard)
- Highest attrition in **Research & Development** and **Sales**
- **30–39 age group** most likely to leave
- Employees in **medium salary band** most prone to attrition
- **Sales Executives** and **Lab Technicians** show highest job-role attrition
