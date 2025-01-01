# CODTECH-TASK2
Name:THARINI.M 
Company:CODTECH IT SOLUTIONS
ID:CT12DVV Domain:Artificial Intelligence 
Duration: December to February 2025.
Mentor: SRAVANI GOUNI

Overview of the Project
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It leverages real-world data to build a robust model that distinguishes between normal and fraudulent transactions. The primary goal is to minimize financial losses for users and institutions by accurately identifying fraudulent activities.

Objectives:

Understand Transaction Patterns:
Analyze transaction data to identify key differences between normal and fraudulent transactions.

Feature Engineering:
Preprocess data by scaling transaction amounts and removing irrelevant features for optimal model performance.

Build a Detection Model:
Develop and train an autoencoder-based anomaly detection model to identify fraudulent transactions effectively.


Evaluate Model Performance:

Use metrics like accuracy and classification reports to assess the model's reliability in detecting fraud.

Dataset Description:
The dataset includes anonymized credit card transaction data, with 31 features:

Time: Seconds elapsed between the first transaction and the given transaction.
Amount: Transaction amount.
Class: Label indicating whether the transaction is normal (0) or fraudulent (1).
Other Features: Anonymized numerical attributes representing transaction details.
The dataset is highly imbalanced, as fraudulent transactions are rare.

Methodology:
1. Data Preprocessing:
Remove irrelevant features such as Time.
Scale the Amount feature using standard scaling techniques.
2. Exploratory Data Analysis (EDA):
Visualize the distribution of normal and fraudulent transactions.
Analyze the transaction amounts for each class.
3. Model Development:
Build an autoencoder to learn patterns from normal transactions.
Use a logistic regression model for classification based on hidden representations.
4. Model Evaluation:
Split data into training and testing sets (80/20 split).
Assess performance using classification metrics such as precision, recall, and accuracy.
