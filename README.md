# Credit-Card-Fraud-Detection.ipynb

📘 Project Overview

This project aims to detect fraudulent credit card transactions using Logistic Regression.
The dataset is highly imbalanced, with very few fraud cases compared to normal transactions.
By applying data preprocessing, under-sampling, and model evaluation techniques, we build a reliable classifier to identify potential fraud.

🎯 Objective

The main goal is to build a Machine Learning model that can accurately classify transactions as fraudulent (1) or legitimate (0) based on given features.

🧩 Steps Involved
1. Importing Dependencies

Used essential Python libraries like:

NumPy

Pandas

Scikit-learn (for model building and evaluation)

2. Loading the Dataset

Loaded the Credit Card Dataset using Pandas and explored it using .head(), .info(), and .describe().

3. Data Analysis & Cleaning

Checked for missing values.

Identified class imbalance (normal vs. fraud).

Separated data into legit and fraudulent transactions.

4. Handling Imbalance (Under-Sampling)

Since the dataset was highly unbalanced, created a balanced dataset by under-sampling normal transactions to match the fraud count.

5. Feature Selection

Separated features (X) and target (Y) variables for training.

6. Splitting the Data

Divided the dataset into:

80% training data

20% testing data

7. Model Training

Trained a Logistic Regression model on the balanced dataset.

8. Model Evaluation

Evaluated model performance using accuracy score:

Training Accuracy: 97.84%

Testing Accuracy: 97.41%

⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Google Colab / Jupyter Notebook

📊 Results

✅ Achieved over 97% accuracy on both training and testing datasets.
✅ Successfully detected fraudulent transactions with reduced false positives.

📂 Dataset

The dataset used is the Credit Card Fraud Detection dataset, available from Kaggle.
It contains 31 columns and over 25,000 transactions.

📈 Future Improvements

Use advanced models like Random Forest or XGBoost

Apply SMOTE (Synthetic Minority Over-sampling Technique)

Perform hyperparameter tuning to improve performance

👨‍💻 Author

Fajlur Rahman
Data Science & Machine Learning Enthusiast
🔗 LinkedIn Profile
