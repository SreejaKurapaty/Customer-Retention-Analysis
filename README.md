# Customer-Retention-Analysis
Predicting customer churn using machine learning to help businesses proactively retain customers. This project uses real-world telecom data and applies multiple classification models to identify customers who are likely to leave the service.

## **Dataset**
**Source:** Telco Customer Churn - Kaggle<br>
**Records:** 7,043<br>
**Features:** Demographics, service usage, account information, churn status

## **Project Objective**
To analyze customer behavior and build predictive models that estimate the likelihood of a customer churning. <br>
**The project aims to:**
Identify key factors influencing customer churn
Build a high-performing machine learning model
Compare model performance using accuracy and ROC AUC
Provide actionable insights for business decision-making

## **Tools & Technologies**
Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)<br>
Jupyter Notebook

**Machine Learning Models:**
Logistic Regression<br>
Random Forest<br>
K-Nearest Neighbors (KNN)<br>
Support Vector Machine (SVM)<br>
Gradient Boosting

## **Exploratory Data Analysis (EDA)**
Identified missing values and handled data types.<br>
Visualized churn rates by contract type, tenure, and monthly charges.<br>
Found that short-term contracts and high monthly charges were key churn indicators.

## **Model Building**
Each model was trained and evaluated using:<br>
**Train/Test Split:** 80/20 <br>
**Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC AUC<br>

## **Final Model Performance:**
| Model               | Accuracy | ROC AUC |
|--------------------|----------|---------|
| Logistic Regression| 81.69%   | 0.8615  |
| Random Forest       | 80.98%   | 0.8605  |
| Gradient Boosting   | 80.55%   | 0.8580  |
| SVM                 | 73.53%   | 0.8166  |
| KNN                 | 77.71%   | 0.7762  |


### **Logistic Regression gave the best overall performance in terms of ROC AUC and accuracy.**

