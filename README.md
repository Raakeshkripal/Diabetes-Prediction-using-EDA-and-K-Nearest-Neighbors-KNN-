# 🩺 Diabetes Prediction using EDA and K-Nearest Neighbors (KNN)

This project aims to analyze and predict diabetes in patients using Exploratory Data Analysis (EDA) and a supervised machine learning algorithm, K-Nearest Neighbors (KNN). The dataset used is the Pima Indians Diabetes Dataset, which is widely used for binary classification problems.

---

## 📌 Overview

This project involves:
- Cleaning and analyzing medical data
- Visualizing data distributions and relationships
- Standardizing features for model training
- Applying the K-Nearest Neighbors classification algorithm
- Evaluating model performance using standard metrics

---

## 📊 Dataset

- **Source File**: `diabetes.csv`
- **Features**:
  - `Pregnancies`
  - `Glucose`
  - `BloodPressure`
  - `SkinThickness`
  - `Insulin`
  - `BMI`
  - `DiabetesPedigreeFunction`
  - `Age`
  - `Outcome` (Target variable: 0 = Non-Diabetic, 1 = Diabetic)

---

## 🔧 Steps Performed

1. **Exploratory Data Analysis (EDA)**
   - Checked for null values, duplicates
   - Used `boxplots`, `histograms`, and `pairplots`
   - Visualized target class distribution

2. **Feature Standardization**
   - Used `StandardScaler` to normalize data before model fitting

3. **Model Training with KNN**
   - Split data into training and testing sets (70/30)
   - Trained KNN with different values of K
   - Plotted training vs testing accuracy to select optimal K

4. **Model Evaluation**
   - Achieved best test accuracy at **k = 13**
   - Evaluated model using:
     - Accuracy score
     - Confusion matrix
     - Classification report (precision, recall, F1-score)

---

## 📈 Results

- ✅ **Max Test Accuracy**: ~78.3%
- 🧠 Best K value: **13**
- Model performs reasonably well in identifying diabetic cases.

---

## 🚀 Future Scope

- 🌐 **Web Interface**: Deploy the model in a web-based frontend for real-time prediction.
- 🔍 **Advanced Models**: Use more robust classifiers like Random Forest, SVM, or XGBoost.
- 📚 **Larger Dataset**: Use a more complex or larger dataset for better generalization.
- 🧩 **Explainable AI**: Add feature interpretation tools (SHAP, LIME) to understand predictions better.

---

## 🤝 Contributing

Feel free to fork the repository or raise issues or PRs for enhancements. Collaboration is welcome!

---

## 👤 Author

**Raakesh Kripal VUK**  
📧 raakeshkripal.vuk@gmail.com

---
