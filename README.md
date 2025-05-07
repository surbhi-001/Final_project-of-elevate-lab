HR Analytics: Predicting Employee Attrition
📊 Project Overview
This project focuses on analyzing employee data to understand the key factors influencing attrition and building a machine learning model to predict whether an employee is likely to leave the company. The analysis supports HR teams in developing targeted retention strategies.

Tools Used: Python (Pandas, Seaborn, Scikit-learn, SHAP), Power BI
Model: Logistic Regression / Decision Tree Classifier
Dataset: IBM HR Analytics Employee Attrition & Performance Dataset

🧠 Objectives
Perform Exploratory Data Analysis (EDA) to uncover trends and correlations in employee attributes.

Build a classification model to predict attrition based on employee data.

Use SHAP (SHapley Additive exPlanations) for interpreting model predictions.

Create an interactive Power BI dashboard to visualize attrition drivers and business insights.

Propose data-driven strategies for reducing attrition.

🔍 EDA Highlights
Explored key variables such as job satisfaction, age, overtime, and work-life balance.

Identified strong relationships between attrition and:

Overtime status

Distance from home

Environment satisfaction

Monthly income

🤖 Model Performance
Trained a Logistic Regression / Decision Tree model.

Evaluated using accuracy, precision, recall, and confusion matrix.

Final Accuracy: xx% (replace with actual)

Confusion Matrix:

lua
Copy
Edit
[[TP  FP]
 [FN  TN]]
📈 Power BI Dashboard
Interactive dashboard with:

Attrition rate by department, job role, age group, and more

Key KPIs and filters

Visual correlation between overtime and attrition

[Include a screenshot or link if hosted]

🧩 SHAP Analysis
SHAP values used to explain individual predictions.

Visualized global feature importance and local explanations.

Top drivers of attrition:

Overtime

Job satisfaction

Monthly income

💡 Recommendations
A PDF report is included with tailored suggestions to reduce attrition, such as:

Reducing mandatory overtime

Increasing job satisfaction through career development

Improving compensation for at-risk roles

📁 Project Structure
bash
Copy
Edit
HR_Attrition_Project/
│
├── data/                    # Raw and cleaned datasets
├── notebooks/               # Jupyter notebooks for EDA and modeling
├── PowerBI/                 # Power BI dashboard file (.pbix)
├── reports/                 # SHAP outputs, PDF report
├── models/                  # Trained models and outputs
├── README.md                # Project overview
