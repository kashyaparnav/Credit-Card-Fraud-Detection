#Credit Card Fraud Detection Using Machine Learning


📌Project Overview

Credit card fraud is one of the most significant challenges faced by financial institutions. This project aims to develop a Machine Learning model capable of identifying fraudulent credit card transactions with high accuracy while minimizing false positives.

The model analyzes transaction patterns and classifies transactions as either Fraudulent (1) or Legitimate (0).

🎯 Objective
Detect fraudulent credit card transactions.
Handle highly imbalanced transaction data.
Compare multiple machine learning algorithms.
Evaluate model performance using fraud-specific metrics.
Build a scalable fraud detection pipeline.

📂 Dataset Information
The dataset contains anonymized credit card transactions made by European cardholders.

Features
Feature	Description
Time	Seconds elapsed between transactions
V1-V28	PCA-transformed confidential features
Amount	Transaction amount
Class	Target Variable
Target Variable
0 → Genuine Transaction
1 → Fraudulent Transaction

🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Imbalanced-Learn (SMOTE)

📊 Project Workflow
1. Data Collection
Load dataset
Explore dataset structure
Understand target distribution
2. Data Preprocessing
Check missing values
Scale numerical features
Handle class imbalance using SMOTE
3. Exploratory Data Analysis (EDA)
Fraud vs Non-Fraud distribution
Transaction amount analysis
Correlation analysis
Feature importance visualization
4. Feature Engineering
Standardize Amount and Time features
Select relevant features
5. Model Building

Implemented:
Logistic Regression
Random Forest Classifier
XGBoost Classifier

6. Model Evaluation

Metrics used:

Accuracy Score
Precision
Recall
F1-Score
ROC-AUC Score
Confusion Matrix

Results
Model	Accuracy	Precision	Recall	ROC-AUC
Logistic Regression	97%+	High	High	Excellent
Random Forest	99%+	Very High	Very High	Excellent
XGBoost	99%+	Outstanding	Outstanding	Excellent

Note: In fraud detection, Recall and ROC-AUC are more important than Accuracy due to class imbalance.

📉 Visualizations

Fraud Distribution
Count Plot of Fraud vs Non-Fraud Transactions

<img width="785" height="458" alt="image" src="https://github.com/user-attachments/assets/2cdc6214-91fb-43cd-a45c-75957e8ae467" />


Transaction Amount Analysis
<img width="784" height="443" alt="image" src="https://github.com/user-attachments/assets/37676dad-274e-4261-8112-4f2fee9c3907" />


Distribution of transaction amounts
Correlation Heatmap
<img width="687" height="581" alt="image" src="https://github.com/user-attachments/assets/649fefb2-fca2-4423-a05b-f1e679af1afb" />


Relationship between features
Confusion Matrix
Visualization of model predictions

 How to Run
Clone Repository
git clone https:https://github.com/kashyaparnav/Credit-Card-Fraud-Detection/tree/main
cd Credit-Card-Fraud-Detection
Install Dependencies
pip install -r requirements.txt
Run Notebook
jupyter notebook

Open:

Credit_Card_Fraud_Detection.ipynb
📁 Project Structure
Credit-Card-Fraud-Detection/
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── Credit_Card_Fraud_Detection.ipynb
│
├── models/
│   └── fraud_detection_model.pkl
│
├── requirements.txt
├── README.md
└── images/
