🛒 Customer Purchase Behavior Prediction

A machine learning classification project that predicts whether a customer will make a purchase based on their demographic, browsing, and transaction behavior.
This project aims to help businesses identify high-value customers and improve marketing strategies through data-driven insights.

📘 Overview

In this project, I developed a predictive model that classifies customers as “likely to purchase” or “not likely to purchase” based on their attributes and online activity patterns.
The dataset has over 50 features.
The project covers the complete ML lifecycle — from data preprocessing and feature engineering to model building, evaluation, and interpretation.

🧩 Problem Statement

Businesses often have vast customer data but struggle to identify which users are most likely to purchase.
This model helps prioritize customers for targeted marketing campaigns, improving conversion rate and customer retention.

⚙️ Workflow
1️⃣ Data Preprocessing

Handled missing values and outliers

Performed target encoding for categorical variables as they have high cardinality

Standardized numerical features

Created new behavioral features like:

Average session duration

Number of items viewed

Days since last visit

Total purchases or amount spent

2️⃣ Exploratory Data Analysis (EDA)

Analyzed purchase patterns across demographics (age, gender, location)

Visualized relationships between features and purchase probability

Identified top influencing features such as income, engagement time, and discount usage

3️⃣ Model Building

Tested multiple models:

Logistic Regression

Random Forest

XGBoost

Support Vector Machine (SVM)

Applied hyperparameter tuning using GridSearchCV

Used class weighting and SMOTE to handle data imbalance

4️⃣ Model Evaluation

Evaluated models using:

Accuracy

Precision

Recall

F1-score

ROC-AUC Curve

Final model (XGBoost) achieved:

Accuracy: 91%

Precision: 89%

Recall: 86%

F1-score: 87%

AUC: 0.93
