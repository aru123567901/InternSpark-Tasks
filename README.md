InternSpark ML Project
Overview
This repository contains the machine learning tasks completed as part of the InternSpark Machine Learning Internship Program. The project demonstrates the complete machine learning workflow, including data preprocessing, model development, evaluation, fairness analysis, explainable AI techniques, and model deployment.
Project Objectives
•	Build and evaluate machine learning classification models.
•	Analyze model performance using industry-standard metrics.
•	Identify and assess potential bias in model predictions.
•	Apply Explainable AI (XAI) techniques for model transparency.
•	Deploy trained models as REST APIs using Flask.
•	Containerize applications using Docker for portability.
________________________________________
Tasks Completed
Task 1: Breast Cancer Classification
Developed a classification model using the Wisconsin Breast Cancer Dataset to predict whether a tumor is malignant or benign.
Techniques Used
•	Data preprocessing
•	Feature scaling
•	Logistic Regression
•	Random Forest Classifier
Evaluation Metrics
•	Accuracy
•	Precision
•	Recall
•	F1-Score
•	ROC-AUC
Visualizations
•	ROC Curve
•	Confusion Matrix
•	Feature Importance Analysis
________________________________________
Task 2: Exploratory Data Analysis
Performed comprehensive exploratory data analysis to understand data distributions, correlations, missing values, and feature relationships.
Key Activities
•	Data cleaning
•	Statistical summaries
•	Correlation analysis
•	Visualization of feature distributions
________________________________________
Task 3: Responsible AI and Bias Analysis
Analyzed fairness and bias using demographic attributes from the Adult Census Dataset.
Fairness Metrics
•	Demographic Parity
•	Equal Opportunity Difference
•	Group-wise Prediction Analysis
Explainability
•	SHAP Summary Plots
•	Feature Impact Analysis
Bias Mitigation Approaches
•	Sample Reweighting
•	Correlation-Based Feature Removal
•	Fairness-Constrained Model Training
________________________________________
Task 4: Model Deployment
Deployed the trained machine learning model as a REST API using Flask and Docker.
Available Endpoints
Endpoint	Method	Description
/health	GET	API health check
/predict	POST	Single prediction
/batch_predict	POST	Batch predictions
________________________________________
Technologies Used
•	Python
•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn
•	Scikit-learn
•	SHAP
•	Fairlearn
•	Flask
•	Docker
________________________________________
Project Structure
InternSpark-ML-Project/
│
├── notebooks/
│   ├── Task1_Classification.ipynb
│   ├── Task2_EDA.ipynb
│   ├── Task3_Bias_Analysis.ipynb
│   └── Task4_Deployment.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md
________________________________________
Installation
git clone https://github.com/YOUR_USERNAME/InternSpark-ML-Project.git

cd InternSpark-ML-Project

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt
________________________________________
Running the Project
Launch Jupyter Notebook
jupyter notebook
Start Flask API
python app.py
API will be available at:
http://127.0.0.1:5000
________________________________________
Results Summary
Metric	Value
Accuracy	97.37%
Precision	97.62%
Recall	97.62%
F1-Score	97.62%
ROC-AUC	99.47%
________________________________________
Future Improvements
•	Hyperparameter optimization
•	Advanced fairness mitigation techniques
•	Cloud deployment
•	CI/CD integration
•	Real-time monitoring
________________________________________
Author
Aruhi Patel
InternSpark Machine Learning Internship Program


