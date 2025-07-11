# Diabetes-Prediction-using-EDA-and-K-Nearest-Neighbors-KNN-
This project aims to analyze and predict diabetes in patients using Exploratory Data Analysis (EDA) and a supervised machine learning algorithm — K-Nearest Neighbors (KNN). The dataset used is the Pima Indians Diabetes Dataset, widely used for binary classification problems.
📌 Overview
EDA (Exploratory Data Analysis) is performed to understand the underlying patterns, relationships, and data distributions.

KNN (K-Nearest Neighbors) is implemented to classify patients into diabetic or non-diabetic groups.

Data Preprocessing, Normalization, and Model Evaluation are key steps in the pipeline.

The model is evaluated using metrics like accuracy, confusion matrix, and classification report.

📊 Dataset
Source: diabetes.csv

Attributes:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (0 = No Diabetes, 1 = Diabetes)

🔧 Project Workflow
Data Cleaning & Exploration

Null and duplicate checks

Summary statistics

Distribution plots

Pairplots and correlation heatmap

Outlier Detection

Boxplots across features

Data Normalization

Using StandardScaler to standardize input features

Model Building

Train-Test split (70-30)

Implementation of KNN classifier

Optimal K value selection using accuracy curves

Evaluation

Accuracy score

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

📈 Results
Best Test Accuracy: ~78.3% at k = 13

The model performs well in classifying diabetic and non-diabetic cases with a balanced precision and recall.

🚀 Future Scope
Web App Deployment: This model can be deployed as a user-friendly web application for real-time predictions.

Advanced Models: Additional classifiers like Random Forest, SVM, or Deep Learning models can be experimented with.

Rich Dataset: Incorporate more diverse and complex datasets for better generalization.

Model Interpretability: Add SHAP or LIME to interpret feature importance.

🛡 License
This project is licensed under the Apache License 2.0 — see the LICENSE file for details.

⚠️ Permission is required to reuse this project or its components commercially or academically. Please contact the author via GitHub or email.

🤝 Contributing
Pull requests and forks are welcome. For major changes, please open an issue first to discuss what you would like to change.

👨‍💻 Author
Raakesh Kripal VUK
📧 raakeshkripal.vuk@gmail.com


