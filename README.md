🍷 Wine Quality Prediction – End-to-End Machine Learning Project

📌 Project Overview

This project demonstrates a complete end-to-end Machine Learning workflow using a real-world dataset.

The goal is to predict wine quality based on its chemical properties and convert the problem into a binary classification task (Good vs Bad wine).

The project covers all major steps involved in building a real-world ML system, from data understanding to model optimization.

🎯 Objective

Understand and analyze the wine quality dataset

Perform data preprocessing and exploratory data analysis (EDA)

Convert the problem into a binary classification task

Train and compare multiple Machine Learning models

Optimize model performance using pipelines and hyperparameter tuning

📊 Dataset Information

File Name: winequality.csv

Rows: Each row represents one wine sample

Columns: Chemical properties of wine

Target Column: quality

Binary Classification Rule

Quality ≥ 7 → Good Wine (1)

Quality < 7 → Bad Wine (0)

🛠️ Technologies Used:-

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🔍 Project Workflow


1️⃣ Data Loading & Understanding

Load dataset using Pandas

Inspect structure using head(), tail(), and sample()

2️⃣ Data Inspection

Check column names, data types, shape, and summary statistics

3️⃣ Missing Value Analysis

Verify missing values using isnull()

4️⃣ Exploratory Data Analysis (EDA)

Analyze wine quality distribution

Visualize quality scores using count plots

5️⃣ Binary Classification Conversion

Create quality_label column for Good/Bad wine classification

6️⃣ Feature & Target Separation

Separate input features (X) and target variable (y)

7️⃣ Train-Test Split

Split dataset into 80% training and 20% testing data

8️⃣ Feature Scaling

Apply StandardScaler for numerical features

9️⃣ Model Training

Trained and evaluated the following models:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

🔟 Model Evaluation

Compare models using accuracy score

Identify best-performing model


1️⃣1️⃣ Pipeline & Hyperparameter Tuning

Create ML pipeline

Apply GridSearchCV for parameter tuning


📈 Results

Tree-based and SVM models performed better due to their ability to handle complex patterns

Feature scaling improved performance for distance-based models

Hyperparameter tuning helped achieve optimal model accuracy

✅ Key Learnings

Importance of data preprocessing and EDA

Handling classification problems in real-world ML systems

Comparing multiple ML models effectively

Using pipelines to avoid data leakage

Improving performance through hyperparameter tuning

🚀 Conclusion

This project reflects a real-world Machine Learning application where data understanding, preprocessing, model selection, and evaluation are equally important.

It provides a strong foundation for building production-ready ML systems.

📁 How to Run the Project

Clone the repository

Open the Jupyter Notebook

Run all cells step-by-step

👤 Author:-

Charu Latha
