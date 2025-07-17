# Employee-Attrition-Prediction 
"Employee Attrition Prediction using Machine Learning with Power BI Dashboard"

This project focuses on analyzing employee data to understand attrition patterns and predict which employees are at risk of leaving the company. Machine learning models are used to forecast attrition, and results are visualized using Power BI to assist HR teams in decision-making.

 # Project Overview
Built multiple ML models like Logistic Regression, Random Forest, Decision Tree, and XGBoost to predict employee attrition.
Used an HR dataset that includes features like age, department, job role, salary, performance rating, job satisfaction, etc.
Created a Power BI dashboard to visualize key HR metrics and model results.
Provides business insights on employee retention based on data trends.

# Files in the Repository

WA_Fn-UseC_-HR-Employee-Attrition.csv : Original HR dataset used for training and evaluation.

model_performance.csv : Summary of accuracy, precision, and recall for all trained models.

Task 1 dashboard.pbix : Power BI dashboard visualizing attrition insights, model results, and key metrics.

# Power BI Dashboard Includes:
Attrition rates by department, job role, gender, and education.
Age group distribution and income-level impact on attrition.
KPI summary cards for total employees, attrition rate, average income, and more.
Actual vs Predicted attrition comparison using ML outputs.
Model performance comparison for business interpretability


# Dataset Source
IBM HR Analytics Attrition Dataset
🔗 Click to view on Kaggle
IBM HR Analytics Attrition Dataset:
 https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-datase

 # How to Run
Clone the repository to your system.
Open hr_attrition_prediction.py in Jupyter Notebook or VS Code.
Run the script to generate prediction and evaluation CSVs.
Open the Power BI dashboard file HR_Attrition_Dashboard.pbix.
Click Refresh in Power BI to load the latest results.

# Future Scope
Add SHAP or LIME interpretability for model transparency.
Deploy using Streamlit or Flask for real-time prediction access.
Add more HR features like promotion history or performance score trends.
Integrate real-time HR data via API for continuous updates.
