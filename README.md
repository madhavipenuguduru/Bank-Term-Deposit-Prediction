# Bank-Term-Deposit-Prediction
This project predicts whether a customer will subscribe to a bank term deposit using the Bank Marketing dataset. It includes data cleaning, feature encoding, outlier handling, age binning, and training a Random Forest model. The model is evaluated using accuracy, confusion matrix, and classification report.

A machine learning-based solution designed to predict whether a customer will subscribe to a bank term deposit. Built using Python and Scikit-learn, this project performs end-to-end data preprocessing, modeling, and evaluation using a real-world marketing dataset from a Portuguese bank.

📌 Introduction
This project helps financial institutions identify clients who are likely to subscribe to a term deposit. By analyzing past marketing campaign data, a Random Forest classifier is trained to predict customer response based on demographic and interaction features.

🚀 Key Features
✅ Load and process data from CSV file (bank-full.csv)
✅ Handle missing values using mode
✅ Detect and handle outliers using IQR
✅ One-hot encode categorical variables
✅ Categorize age into groups (Youth, Adult, Senior)
✅ Train a RandomForestClassifier
✅ Evaluate with:
Accuracy
Confusion Matrix
Classification Report
✅ Display top feature importances
🛠 Technologies Used
Technology	Purpose
Python	programming language
Pandas, NumPy	Data manipulation and processing
Matplotlib, Seaborn	Visualization of data and results
Scikit-learn	Machine learning tools and models
Jupyter Notebook	Interactive development environment
⚙ Workflow Overview
Data Loading
Load bank-full.csv into a DataFrame.

Preprocessing

Fill missing values
Encode target and categorical columns
Create AgeGroup bins
Handle outliers in balance and clip duration extremes
Drop unnecessary columns (pdays, previous)
Feature Preparation

One-hot encoding for categorical data
Feature scaling using StandardScaler
Split into train-test sets
Modeling

Train a RandomForestClassifier on the processed data
Evaluation

Compute accuracy, classification report, and confusion matrix
Extract and rank feature importances
📈 Model Performance
Accuracy: 90.39%
Classification Report:
Precision, Recall, and F1-score for both classes
Confusion Matrix:
👩‍💻 Contributor
V.Venkata Sravani

📩 Feel free to reach out for any questions or collaboration opportunities!
