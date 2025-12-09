# employee-attrition-analysis
Machine Learning project for predicting employee attrition.

## 1. Title
Employee Attrition Analysis and Prediction

## 2. Project Description
This project focuses on predicting employee attrition using machine-learning techniques.  
Using the IBM HR Analytics Employee Attrition dataset, the project analyzes key factors influencing employee turnover and builds predictive models to help organizations identify employees who may be at risk of leaving.  
The workflow includes data preprocessing, exploratory analysis, model training, and evaluation using well-established ML methods.

## 3. Features
- Data cleaning and preprocessing  
- Encoding of categorical variables  
- Handling class imbalance using **SMOTE**  
- Scaling numerical features  
- Training two predictive models:
  - Logistic Regression  
  - Decision Tree Classifier  
- Evaluation using:
  - Accuracy  
  - Precision & Recall  
  - Confusion Matrix  
  - ROC-AUC Curve  
- Visualization of model performance and feature importance  

## 4. Technologies Used
- Python 3  
- Pandas  
- NumPy  
- Scikit-Learn  
- Imbalanced-Learn (SMOTE)  
- Matplotlib  
- Seaborn  
- Jupyter Notebook
  
## 5. Project Structure

├── data/
│   └── employee_data.csv
├── notebooks/
│   └── attrition_analysis.ipynb
├── models/
│   ├── logistic_regression.pkl
│   └── decision_tree.pkl
├── README.md
└── requirements.txt


## 6. Installation Steps
Run the following command to install the project dependencies:

pip install -r requirements.txt

## 7. How to Run
1. Open a terminal and launch Jupyter Notebook:
jupyter notebook
2. Open the file:
attrition_analysis.ipynb

## 8. Dataset Info
Dataset: IBM HR Analytics Employee Attrition Dataset
Source: Kaggle
Target Variable: Attrition — Yes / No
Includes features related to:
Demographics
Job roles & departments
Compensation
Performance metrics
Work environment factors


