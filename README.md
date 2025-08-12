🚢 Titanic Survival Analysis – EDA

📌 Overview
This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset, aiming to uncover survival patterns based on passenger demographics, travel class, and other features. The analysis is based on the train.csv file from Kaggle’s Titanic competition.


📁 Titanic_EDA
 ├── Titanic_Train_EDA.html    # Detailed EDA report
 
 ├── train.csv                  # Dataset
 
 ├── README.md                  # Project Documentation
 
 └── EDA_Notebook.ipynb         # Python code for EDA
 


🛠 Steps Performed
1️⃣ Data Loading & Understanding
Loaded the dataset using Pandas.

Checked data types, column names, and basic statistics.

Verified dataset shape: Rows = X, Columns = Y.


2️⃣ Data Cleaning
Handled missing values for Age, Embarked, and Cabin.

Dropped irrelevant columns like PassengerId (non-informative for survival prediction).

Converted categorical features to the correct data types.

3️⃣ Exploratory Data Analysis
Univariate Analysis – Distribution of numerical and categorical variables.

Bivariate Analysis – Relationship between features and survival.

Visualizations:

Survival count by gender.

Survival rate by passenger class (Pclass).

Age distribution of survivors vs. non-survivors.


